# Photo Tools: notes for Claude

A personal suite of browser-only photo/video tools, published with GitHub Pages at
https://lopxfi.github.io/Photo-Tools-Personal/ (owner renamed from `latieros` to `lopxfi` in Oct 2026).

## How the repo is laid out
- The top-level files **are** the site. There is no source folder and no build step: edit the `.html` pages directly.
- Each tool is one self-contained HTML page (styles + script inline). Every page starts with the same head block
  (doctype, manifest, icons, offline registration, and the light/dark switch block `#pt-theme-css` + `#pt-theme-js`,
  which adds the switch next to the page's `<h1>`, starts in dark, and keeps a choice in localStorage `pt-theme`). Keep it identical
  when adding a tool; `build.py check` compares the switch block across pages.
- `index.html` is the home page; `share.html` receives files from the phone's Share menu; `sw.js` is the offline worker.
- `vendor/mediapipe/` is the background remover used by Video Layers (see its README). `.tflite` models can't be served
  inside Claude artifacts, so `video-layers.html` falls back to `<model>.tflite.txt` (base64) when the `.tflite` is missing.
- `dev/` holds helpers only (not part of the site). `dist/` is scratch output and is git-ignored.
- Every tool has three layouts: phone (`max-width:900px`), a plain desktop, and a wide screen (`min-width:1440px`, the
  `/* wide screens */` block at the end of each page's CSS). On wide screens the page uses the whole width, the settings sit on
  both sides of the picture (the shared `ptWide`/`ptSplit`/`ptMove` helpers move the existing sections into a `.pt-left`
  panel), the main buttons go above the picture, and the `foldSections` fold-outs that phones use are turned on too, with
  the open sections remembered in localStorage (`<tool>-open`). Motion Comic and Visual Novel show the Pages/Scenes tab on
  the left and the other tabs on the right (`ptDual`). Keep the phone and plain-desktop looks unchanged when touching these.

## Workflow after changing anything
1. `python3 dev/build.py stamp` — syncs the in-Claude tool links (`const ART=` in the older tools) from
   `dev/artifacts.json` and bumps `VERSION` in `sw.js` so installed copies pick up the change.
2. `python3 dev/build.py check` — pages, offline list (`FILES` in sw.js), index links and tool switchers must agree.
3. `python3 dev/test.py` — opens every page (desktop + phone, top-level + framed like an artifact) in headless
   Chromium; fails on script errors, 404s, sideways scrolling on phones, broken switching, models not loading.
4. Commit and push to `main`; GitHub Pages serves `main`.

## Test copy in Claude
- `python3 dev/build.py artifact` stages the whole site into `dist/site/` and writes `dist/site.publish.json`
  (`file_path`, `files` map, `capabilities`, and the existing artifact `url`). Publish with the Artifact tool using those
  values; keep `capabilities: {downloads: true}` or saving won't work inside Claude.
  Pass `url` from a new session so it updates the same artifact instead of making a new one.
- `python3 dev/test.py --artifact [--shots]` tests the staged copy (screenshots go to `dist/shots/`).
- `--tool <page>.html` stages a single tool, for the older one-tool-per-artifact copies listed in `dev/artifacts.json`.
- When adding a tool: add it to every page's `.switch` nav, `index.html`, `FILES` in `sw.js`, the README,
  and `dev/artifacts.json` once it has an artifact link.

## Conventions
- User-facing text is plain and friendly, no jargon. Everything runs on the device; nothing is uploaded.
- End commit messages with the attribution lines the session provides.
