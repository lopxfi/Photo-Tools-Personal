# Photo Tools

A small set of personal browser tools for dressing up photos, making short videos and cleaning up photo and video files.

**Open it:** https://lopxfi.github.io/Photo-Tools-Personal/

- **Everything runs in your browser.** Photos, videos and sounds never leave your device, and nothing is uploaded anywhere. The one exception is [Outfit Tags](#outfit-tags), which sends the photo you pick to an AI model so it can read the outfit.
- **Your work is kept automatically.** Each tool saves its work in the browser (videos and photos included), so you can close the page or switch tools and pick up where you left off.
- **It works offline.** Install it as an app on your phone or computer and it runs without internet.
- **Share straight from your gallery.** On Android, once the app is installed, it shows up in the Share menu for photos, videos and sounds. Pick it, then pick the tool.
- **Tools pass work to each other.** A framed photo from Photo Frame Studio or a video from Chat Reel goes straight into Video Layers with one tap.
- **Search engines are asked not to list it** (every page has `noindex, nofollow`).
- **Made for big screens too.** On a wide computer monitor each tool spreads out: the picture or video in the middle with its buttons above and below, and the settings on both sides in sections you can fold away. Phones and smaller windows keep the compact layout.

| Tool | What it does |
|---|---|
| [Photo Frame Studio](#photo-frame-studio) | Puts a photo inside a frame: social posts, phone screens, chats, camera screens, prints, comics, covers and newspapers. Takes a photo or a video. Frames one photo or a whole batch. Exports an image, or a video for videos and the animated chats. |
| [Photo Splitter](#photo-splitter) | Cuts one photo into 2, 3 or 4 pieces that join back into the whole picture as you swipe through a post on X, with your own cut lines and your choice of which piece comes first. |
| [Chat Reel](#chat-reel) | Turns a text conversation into a video, timing every message on a timeline. Group chats, reactions, replies, voice notes and unsent messages, in iPhone, Android, DM, WhatsApp-style, Discord-style or lock-screen looks, or as a sci-fi transmission screen, a retro game cutscene, a video call, a social post with comments, or bubbles over your own video. |
| [Metadata Scrubber](#metadata-scrubber) | Strips prompts, location and hidden data out of photos and videos and saves clean copies under random names, optionally under a size limit. |
| [Caption Maker](#caption-maker) | Puts words on a picture (captions, dialogue, speech bubbles, titles) in about 60 fonts or your own, with outlines, shadow, glow, 3D and curved text. |
| [SFX Maker](#sfx-maker) | Turns a typed sound effect into manga lettering (BOOM, ドカーン): letters along a curve, comic, brush, lightning and other styles in free fonts, outlines, halftone, 3D, motion and jagged edges, with a sheet of random ideas. PNG, SVG or layers. |
| [Effect Lines](#effect-lines) | Manga effect lines and screentones: focus lines, black flash, speed lines, rain, cross-hatching and rope hatching, halftone, gradients, 19 patterns, sparkles, petals and more. Drag the center, shape with sliders, stack layers, save as transparent PNG, SVG or a ZIP by layer. |
| [Panel Layouts](#panel-layouts) | Manga and comic page layouts in batches of 12, 24 or 48 from a seed: orderly, standard, action or splash pages, slanted borders, bleeds and split panels, right-to-left or left-to-right. Drag borders, remove panels, mutate a layout into variations, and save as SVG or PNG with a clear, white or black background. |
| [Bubble Maker](#bubble-maker) | Manga speech and thought bubbles: 15 styles (classic, thought, shout, whisper, shaky, radio, narration, shoujo, pop, echo, horror and more), any words in about 100 fonts or your own, tails you point by dragging, patterns, double lines, shadows and decorations. Several bubbles on a page, random ideas, a bubble sheet to cut up, and saving as see-through PNG, SVG or a ZIP of each bubble. |
| [Watermark](#watermark) | Puts your name or logo on one photo or a whole batch, with ready-made looks (corner signature, label, stamp, proof band, tiled) or your own saved watermarks. |
| [Background Remover](#background-remover) | Takes the background out of photos and videos: people, animals, everyday things, a plain background or green screen, or any color you pick like a chroma key. Touch-up brush for photos, and see-through, color, blurred or picture backgrounds. |
| [Video Layers](#video-layers) | Puts pictures, videos, text, music and your voice together and exports a new video or GIF. Automatic background removal, green screen, motion paths with keyframes and one-tap layouts. |
| [Delivery Reel](#delivery-reel) | Plays out an order from a made-up delivery app, from placed to delivered, and ends on the delivered screen. A courier chat on the way and a doorstep photo or video that opens full screen. |
| [Visual Novel](#visual-novel) | Scenes with characters, expressions and choices that branch. Play it in the page, export a video of a path, or save a playable file anyone can open. |
| [Motion Comic](#motion-comic) | Panels pop in, then their bubbles, with sound words, speed lines, cut-ins and page turns. Scrolls like a webtoon or turns pages like a book. |
| [Outfit Tags](#outfit-tags) | Reads the outfit in a photo or a piece of anime art and turns it into Danbooru tags or prompts for AI image generators, with characters, series and named outfits. Sends the photo to an AI model to read it. |

Every tool has a switcher at the top to jump to another tool. Your work is saved before it switches.

---

## Photo Frame Studio

Pick a frame, add a photo, change the words, drag things into place, export.

### Frames

The frames sit in four categories: **Social & phone**, **Cameras**, **Prints** and **Covers & comics**. Tap a category to drop down its frames. A closed category shows which of its frames is picked, or how many it has.

**Social & phone**
- **Story caption:** a full-screen story with a see-through caption bar you can slide, a big sticker word and a profile header.
- **Social post:** a feed post with username, location, likes, caption, comments and time. Light or dark.
- **Short video (TikTok-style):**
  - The For You and Following tabs, plus the like, comment, save and share rail with a spinning sound disc.
  - Caption with bold hashtags, the sound line and a link pill.
  - Text on the video in four styles.
  - Phone or video-only layout.
- **Phone camera:** a phone viewfinder with camera modes, zoom buttons, grid, recording timer and last-photo thumbnail.
- **Gallery viewer:** an Android-style photo view with date header and share, edit, favorite and delete buttons.
- **iPhone messages, Android messages, Social DM (Instagram-style):** text threads.
  - Write one message per line, starting your own with `me:`.
  - Add time dividers with `--`.
  - Place up to three chat photos with `[1]`, `[2]`, `[3]`. Each one can show as a photo, a video or a shared post.
  - Choose bubble colors, status lines and light or dark mode.
- **Video page (YouTube-style):** a player with chapter progress bar, title, channel, subscribe button, likes and description.
- **Microblog post (X-style):**
  - Verified badge, post text, optional link and photo, time, views and counts.
  - The photo can be landscape, square, portrait or its original shape.
  - Dark, dim or light.
- **Chat app post (Discord-style):** a channel message with profile picture, name color, time, an optional reply, your photo attached, emoji reactions and a follow-up message. Dark or light.
- **Forum post (Reddit-style):** community, who posted and when, title, flair, text, your photo, score with your up or down vote, comments and awards. Dark or light.
- **Now playing:** a music player screen or a share card, with your photo as the album art, song, artist, album, progress bar, a lyric line and a background drawn from the photo's colors.
- **Lock screen:** your photo as the wallpaper with the big clock, date and a stack of notifications you write. iPhone or Android.

**Cameras**
- **Camera viewfinder:** Fuji-, Canon- or Nikon-style live view.
  - Shutter, aperture, ISO, exposure compensation, shots left and battery.
  - Grid or crop overlay, and a focus box you can drag.
- **Security camera:**
  - Single, split or quad view, with a photo of your choice for each camera.
  - Night vision, color or black and white.
  - Timestamp, camera names, REC light and a motion box.
- **VHS camcorder:** a home-video look in 4:3, 16:9 or 9:16, with PLAY, REC or PAUSE in the corner, time and date, tape counter and speed, battery, warm, faded, cool or B&W color, a tracking glitch and scanlines.

**Prints**
- **Polaroid:** a handwritten caption and date, frame colors and film looks.
- **Instax:** mini, square or wide, with plain, striped or confetti borders.
- **Film strip:** a 35mm strip (across or down) or a whole contact sheet, with up to four of your photos, film edge printing and frame numbers, a note on the sheet and a grease-pencil mark around your favorite frame.

**Covers & comics**
- **Manga panel:** an inked look, plus four kinds of text, each with its own shapes:
  - a speech bubble (round, box, jagged or whisper);
  - a thought bubble (cloud, puffy, soft or narration box);
  - a shout (rays, burst, spiky or electric);
  - a sound effect in four lettering styles.
- **Magazine cover:**
  - Masthead, cover star, cover lines, a right-hand column, issue date and price.
  - Several font choices for each block.
  - A barcode you can randomize.
- **Movie poster:** Blockbuster, Festival (with laurel), Horror or Retro styles, with cast, tagline, credits block and release line.
- **Book cover:** Thriller or Literary styles, with title, tagline, author and a review quote.
- **Newspaper front page:** Classic or Tabloid, with paper name, motto, date, price, edition, headline, subheadline, byline, your photo with caption, and story columns.

### Editing
- **Add a photo or video:** with the button or by dropping it on the preview. Photos can also be pasted.
- **Move things:** zoom and drag the photo or video, drag text and bubbles where you want them, or reset everything with **Re-center**.
- **Second photo:** frames with a profile or contact picture can take one, and it's shared by every frame that uses one.

### Animated chats
- **Play it:** the iPhone, Android and Social DM frames can play like a real conversation, with typing dots and messages popping in. At the end, a photo can be tapped open full screen.
- **Settings:** speed, typing dots, which photo opens, how long to hold at the end, and looping.
- **Make video:** saves it as **WebM**, **MP4** or **GIF**, at best quality, half size, or under a size limit you choose (for example, under 5 MB).

### Videos in a frame
- **Any frame takes a video:** add one in place of the photo and it plays inside the frame. **Play** and the slider under the preview watch it in place.
- **Frames that move with it:** the progress bar on **Short video** and **Video page** (with the player's time), the recording timer on **Phone camera**, the timestamp on **Security camera**, the tape counter on **VHS camcorder** and the time played on **Now playing** all count along with the video.
- **Sound:** turn the video's sound on or off for the preview. Exports can include it either way.
- **Make video:** saves the framed video as **MP4** or **WebM** with its sound, or as a **GIF**, at best quality, half size or under a size limit.
- **Remove video** goes back to your photo. Your video is kept in the browser with the rest of your work, but it isn't saved in project files, and **Batch** stays photos only.

### Batch
- **Batch** puts the frame you have open on many photos at once, each centered in the frame with the same words, and gives them all back in one ZIP (PNG or smaller JPG).
- Photos shared from your gallery come in ready to batch.

### Saving
- **Export image:** saves a PNG. **Copy image** puts it on the clipboard. **Split for X** sends it to the Photo Splitter, and **Use in Video Layers** sends it straight into a video.
- **Save project / Open project:** keeps everything, photos included, in a `.json` file you can open again on any device.

---

## Photo Splitter

Cuts one photo into pieces that join back into the whole picture when you post them together on X.

### Swipe (how X shows several photos now)
- X shows 2 to 4 photos side by side at the same height. The first one is shown big and you swipe right to left through the rest, so the picture carries on from one photo to the next.
- **Your own cuts:** drag the white lines in the preview to put each cut where you want it. Each piece keeps its own width, so you can cut around a face or a detail.
- **All the same shape:** every piece 4:5, 1:1, 3:4, 2:3, 9:16 or 16:9 instead.
- **Which piece goes first:** pick the left, middle or right piece as the first photo, since that's the one X shows big. The rest follow to the right, then come back around to the left side. For example, a wide drawing cut in three can open on the face in the middle, then the right side, then the left.
- **Gap:** optionally leave out a sliver at each cut to match the space X puts between photos.

### Older X grid view
- **4-photo grid** (2 × 2), **3-photo grid** (one tall, two stacked) and **2-photo grid** (side by side), in X's 16:9 box. The splitter leaves out the thin line X draws between photos (0.5% by default) so everything lines up across it.

### Preview and framing
- The preview shows your photo with the cuts on top and a mock X post underneath, in light, dim or dark, with each piece numbered in posting order.
- Drag the picture to move it, scroll or pinch to zoom, or tap **Show the whole photo** to fit all of it with a blurred or colored border.

### Saving
- **Save the photos:** each piece is saved numbered in posting order (`photo-1-of-3.jpg`…), as JPG (small enough for X) or PNG. Or save them all as one ZIP.
- **Share (phones):** on the website or installed app, **Share** sends all the pieces straight to the X app in order.
- Pieces are as sharp as your photo allows, up to 4096 pixels a side, X's limit.

---

## Chat Reel

A timeline editor for text conversations that you export as a video.

### Messages
- **Adding:** add their messages, your messages, photos and time dividers.
- **Editing each message:** reorder it, duplicate it or switch who sent it.
- **Photo messages:** can show as a photo, a video or a shared post (with an account name). They can be tapped open full screen after they arrive.
- **Real video messages:** give a video message an actual clip. It plays silently in its bubble after it arrives, then from the start with its sound when it's tapped open full screen, staying open for the whole clip (or as long as you choose). Its sound is recorded into WebM and MP4 exports. Clips are kept in the browser with your work but aren't saved in project files.
- **Group chats:** add up to six more people, each with a name, color and photo, and pick who sends each message. Names show over their bubbles and the header shows the group.
- **Reactions:** an emoji pops onto a bubble a moment after it arrives, from them or from you, with its own sound.
  - Each style offers its own reaction row (iPhone tapbacks, Android's, WhatsApp-style's and so on).
  - **All emojis** opens a picker with every standard emoji by group, a search box, skin tones and your recently used ones.
- **Emojis in messages:** **Add an emoji** under the message text uses the same picker, so there's no need to look emojis up and paste them.
- **Replies:** a message can quote an earlier one, the way each app shows it.
- **Voice notes:** a voice message bubble with a waveform and length. Add a real recording and it plays when the note arrives, with the waveform moving along.
- **Unsend:** a message can vanish after a moment and leave "You unsent a message" (or "deleted", depending on the style) behind.

### Timing
- **Per message:**
  - the pause before it;
  - typing dots, with the typing time set by hand or worked out from the message length;
  - for your own messages, typing it out on the on-screen keyboard, with the time set by keyboard speed (slow, normal or fast).
- **Transmission style:** each line has a speaking time instead (how long it takes to type out on the screen), set by hand or from its length.
- **Overall:** a pause at the start and a hold at the end.
- **Timeline:** drag the blocks to change the pauses, how long typing lasts, and how long a photo stays open.

### Look
- **Style:** iPhone, Android, Social DM, WhatsApp-style (wallpaper, ticks and times inside bubbles) or Discord-style (names, avatars and time stamps), light or dark.
- **Lock screen:** their messages arrive as notifications over a wallpaper, newest on top, with the app name, date and your own wallpaper photo.
- **Start on the lock screen** (any chat style):
  - Their first messages pop up as notifications on the lock screen.
  - You choose how many, from their messages before your first reply.
  - After a pause you set, the top notification is tapped and the chat opens out of it.
  - The rest of the conversation then plays in the chat. The timeline marks where it opens.
- **Transmission:** the conversation as a call on a sci-fi comms screen, with scanlines, a call timer and lines that type out as subtitles.
  - **Screen shape:**
    - **Widescreen (16:9)** keeps both of you on screen, contact on the left and you on the right. Whoever is talking lights up with a moving voice meter, the line types out in the middle, and the last few lines stay above it as a transcript.
    - **Tall (phone)** shows one person at a time and cuts through static when the speaker changes.
  - **Screen color:** amber, green, blue, ice, violet, rose, red or white, or any custom color (the darker and lighter shades are worked out from it).
  - **Photos:** the contact photo and your own photo are tinted to the screen color; without one, an outline stands in. In a group, the person talking on their side takes the screen.
  - **Call:** it can open with an incoming-call screen and end with the screen switching off and "Transmission ended". The timeline marks where it connects and ends.
  - Photos, posts, voice notes, reactions, replies and unsent lines all show on the screen, and photos still open full screen.
- **Retro game:** the conversation as an old-school game cutscene, widescreen or tall (9:16).
  - **Talking portraits:** theirs on the left, yours on the right, in game windows with name tabs. Whoever is talking lights up and bobs; the other dims. Photos become chunky pixel portraits; anyone without one gets a drawn pixel face that moves its mouth and blinks. In a group, the left portrait switches to whoever on their side is talking.
  - **Text box:** lines type out letter by letter in a pixel font, with blips (the keyboard sound setting) and a ▼ when the line is done. Box colors: blue, black, forest, crimson or parchment, with an all-caps option.
  - **Scene:** a field, a town at night, a dungeon, your own photo turned into pixels, or plain black.
  - Photos appear in their own window with a little fanfare, reactions pop up in a balloon over the portrait of whoever reacted, and time dividers become chapter cards.
  - **Opening and ending:** an optional title screen ("PRESS START") with your own title, and a "To be continued..." or "The end" card.
- **Video call:** the conversation as a video call, widescreen or tall (9:16).
  - **Tiles:** everyone the same size, or whoever's talking big. The person talking gets a colored ring and a moving mic.
  - **Cameras:** give them and you a short video clip that loops as the camera. Otherwise their photo is used, gently moving like a live feed; without a photo, initials show like a camera that's off.
  - Messages show as live captions, word by word. Photos, videos and posts are shared on screen ("Maya is presenting"), reactions float up from whoever reacted, and time dividers show as a note at the top.
  - **Start and end:** you call them or they call you (with ringing), or start already on the call; it can end with "Call ended" and the call length.
- **Social post:** a post with its comments filling in underneath, light or dark.
  - **The post:** a photo, a silent looping clip, or a text post, with the poster's handle, caption, time and a like count that ticks up through the reel. It's your post (your comments get an Author tag) or theirs.
  - **Comments:** their messages are comments from the contact and anyone under Group chat; yours are typed into the comment box. A reply nests under the comment it answers, a reaction is a like on that comment (its heart pops, with a count you set), and an unsent comment becomes "Comment deleted". Photo messages show as picture comments.
- **Over your video:** chat bubbles floating over a video clip or photo of your own.
  - **Bubbles:** the iPhone, Android, Social DM or WhatsApp-style look, light or dark. Older messages fade into the video as they scroll away.
  - **Shape:** matches the background, or 9:16, 4:5, 1:1 or 16:9.
  - **Placement:** where the chat sits, how big it is, how much shade goes behind it, and whether their name shows above it.
  - The background video plays from the start and loops if it's shorter. Its own sound can be kept in the export.
- **Contact:** name or username, contact photo, status line, avatar color and clock.
- **Bubbles:** your bubble color (blue, green for SMS, purple or gradient) and the line under your last message (Delivered, Read, Seen…), which always sits clear of the message box.
- **Message box at the bottom:**
  - **Auto** hides it when none of your messages are typed out on the keyboard, so the messages just appear and send on their own.
  - **Always** keeps it, like the real app.
  - **Only while typing** slides it up with the keyboard.

### Sound
- **Built-in sounds:** for sending, replying, keyboard typing and opening a photo (Pop, Chime, Click, Tap or silent), with a volume control.
- **Transmission sounds:** a ring for the incoming call, a burst of static when it connects, a blip as each line starts, soft ticks while it types out (the keyboard sound setting) and a tone when it ends. They're also in the built-in list (Signal, Static, Line, Off) for any message.
- **Retro game sounds:** text blips, a tick as each line starts, an item fanfare for photos, an emote chirp for reactions, a chapter chime, a coin sound for the title screen and a jingle for the ending.
- **Video call sounds:** ringing (or a ringtone when they call you), a join chime when it connects and a leave tone when it ends.
- **Per-message sounds:** any message can have its own sound.
- **My sounds:** upload your own sound files (MP3, WAV, M4A). They're kept in the browser and recorded into the video.

### Export and projects
- **Formats:** WebM, MP4 or GIF, at best quality, half size or under a size limit. Sound, voice notes included, can be included in WebM and MP4.
- **File name:** starts as a random name (like `chat-k3m9qx.mp4`) that doesn't give anything away. Type your own, or tap 🎲 for a new random one.
- **Use in Video Layers:** sends the finished video straight into Video Layers.
- **Projects:** save and open them as files. Work is also kept automatically. Video clips (video messages, a background video, call cameras) are kept in the browser with your work but aren't saved in project files.

---

## Delivery Reel

An order from a made-up delivery app, played out as a video: placed, being prepared, on the way, nearly there, delivered.

### The app
- **Three made-up apps:** Snackrun, Forkful and Plateful, each with its own name and colors, so the reel can't be mistaken for a real service. There's no way to type in a real app's name.
- **Notification sounds** can be turned on or off.

### Your order
- **Restaurant:** a name and an emoji icon.
- **Order:** up to six items with quantities and prices, plus delivery fee, service fee, tip and currency sign. The total is worked out for you.
- **Delivery:** a place name ("Home"), an address, and leave at the door or hand it to me.
- **Courier:** name, rating, how they get there (and a description of the vehicle), and an optional photo. Their initial stands in without one.
- **Times:** the order time and the delivery time; the phone's clock runs from one to the other over the reel. Also how many minutes away they are when they pick it up.

### On the way
- **Map:** made-up streets with the courier moving along the route. Shuffle for a different route.
- **Chat with the courier:** none, when the route starts, or halfway along. Up to eight messages from either side; theirs show typing dots first and yours are typed out. Normal or quick pace.
- **Timing:** how long each stage lasts, on sliders.

### The end
- **Doorstep photo or video:** shows on the delivered screen. Without one, a drawn doorstep with the bag stands in.
- **At the end:** leave it in the card, tap it open and close it again, or tap it open and end on it.
- **Ending:** just the screen, a screenshot flash, or the flash with the corner preview.
- **Confirmation picture:** saves the delivered screen as a picture on its own.

### Export
- **Formats:** WebM, MP4 or GIF, with the same quality and size-limit choices as Chat Reel. Work is kept in the browser.

---

## Visual Novel

Write a branching story and play it, export it, or hand it to someone as a file they can play.

### Scenes
- **Steps fold to one line each** (what it is, who, what it says, ⏱ if you changed its timing). Tap one to open it and preview from there; tapping anything on the timeline opens its step too. **+ Add a step…** is a dropdown at the bottom that stays in reach, and **Open all** shows every step in full. On a computer the writing panel scrolls on its own, so the preview stays in view.
- **Steps:** a line (someone says something, with an expression and where they stand), narration, a choice, show or hide someone, change the background, a picture, a title card, an effect (shake or flash), a sound, music, go to another scene, or the end. Reorder, duplicate and delete them; tap one to preview from there.
- **Picture:** a picture, GIF or video pops up in the middle and the scene darkens behind it (choose how much). It either **stays up** while the next lines are written over it (until a **Remove picture** step, another picture or the next scene; tick *Pause on it* to wait for a tap) or **flashes, then goes** after the time you set. Size and place it with sliders, or drag it on the stage and pull its corner. Frames: plain, white border, rounded or snapshot. It can come in with a pop, fade, zoom, slide, drop or spin, and move with a slow zoom in or out, a pan, a drift, float, sway, heartbeat or shake. An optional white flash when it appears.
- **Choices:** up to four options, each leading to a scene. When you play it, you tap the one you want; a radio button marks which one the video takes.
- **Scenes:** the first one is where the story starts. Each has its own background.

### Characters
- **Cast:** every character as a tile with their face, how many expressions they have and how many lines they speak. Tap one to edit it, or make a new one.
- **Profile:** name, name color, where they usually stand, size, higher or lower, and face the other way (mirror). Tap the portrait to see them on the stage.
- **Expressions:** all of a character's expressions in one gallery. Rename, preview on the stage, replace, make one the default, or delete (it tells you if a scene uses it). Each one has **Add to scene**: pick a scene, show them or give them a line, and where they stand; it goes in after the step you have selected, and you land on it ready to type.
- **Moving portraits:** an expression can be a picture, a GIF, an animated WebP or PNG, or a video (MP4, WebM). Videos and GIFs play on a loop without sound, in the preview, the video export and the playable file. A see-through WebM (from Background Remover, say) stands on the scene like a cut-out; for a video or GIF shot on a green screen, tick **Remove green screen**.
- **Adding:** pick several files at once or drop them on the gallery; each becomes an expression, named from its file name ("mina_happy.gif" becomes Happy).
- **In the story:** every scene a character is in, one tap to jump there.
- **Duplicate** a character with all their expressions, or remove one.
- **Drawn stand-ins:** without your own art, a drawn character with eight expressions (neutral, happy, sad, angry, surprised, shy, thinking, smug), four hair styles, hair colors, skin tones, outfit and eye colors. Whoever is talking lights up; the others dim.
- In the Scenes tab, Line and Show steps pick the expression from a row of faces.

### Backgrounds
- Six built-in scenes (field, sunset, night platform, room, hallway, black) or your own pictures, GIFs or videos (they loop), cropped to fill.
- **Scene changes:** crossfade, cut, through black, through white, wipe, slide, iris, dissolve, blinds or pixelate, for the whole story or one scene.

### Look
- Six screen shapes: widescreen 16:9, classic 4:3, cinema 21:9, square 1:1, post 4:5 and tall 9:16 (phone); nine text-box styles (Glass, Classic, Paper, Minimal, Neon, Grail, Ruin with full-screen text pages, Retro, Letter); accent color; ten letterings; text speed; how lines appear (typewriter, fade in, word by word, rise up, scroll up, bounce in, or all at once); a title screen and credits.

### Sounds
- Little sounds made in the page for text, taps, choices, scene changes, cards and effects, in Classic, Soft or Retro style, or none.
- **Your own sounds:** MP3, OGG, WAV or M4A, many at once (a whole sound pack). Use them in Sound and Music steps or for any of the events above. They're kept in the browser and go into the project and the playable file.

### Branching
- **Choices** send the story to different scenes. Each option can go to a scene or carry on in the same one.
- **Remembered values** (under the scene list): numbers the story keeps as it goes, like points, trust or 1/0 for whether something happened. An option can add to one or set it when it's picked (**⑂** under the option), and can be shown **only if** a value is high enough, low enough or exactly something.
- **Change a value** and **Check a value** steps: change a value anywhere, or send the story to one scene or another depending on it (for example, a good or a lonely ending).
- **Map** (next to Play it and Watch): every scene as a box, with arrows for choices (labelled with the option), Go to steps and checks. The path the video takes is in orange.
  - Tap a scene to write in it, ▶ to play from it, and + to branch out to a new scene.
  - Drag scenes to arrange them, or press **Arrange**.
  - Drag from a scene's ● to another scene to connect them, as a choice option or as "always go on", or drop it on an empty spot to start a new scene there.
  - Tap an arrow's label to edit that choice.
  - Scenes nothing leads to, links to deleted scenes and empty scenes are listed so you can fix them.
- **Branches in Watch:** above the timeline, each choice on the path has a dropdown and ‹ › arrows to switch which way it goes. Later choices change to match. **Path** lists every way through the story with its ending and length, and picking one follows it. The timeline's Scene row has a ⑂ switcher at each choice too. Whatever path you pick there is the one the video records.

### Playing and exporting
- **Play it:** tap (or Space, Enter, or 1–4 for choices) to move through it in the page.
- **Watch:** the video path; lines move on by themselves and each choice takes the marked option. A timeline under the preview shows it row by row:
  - **Rows:** Scene, Story (every line, narration, card, choice, picture that pauses, and the end), Background, one row per character, Picture, Effects, **Sound FX** and **Music**.
  - **Sound FX and Music** are always there. 🔊 mutes that row in the preview only; the video and the playable file keep it. **+** adds a sound effect, or starts the music, right at the playhead (it opens the new step so you can pick the sound).
  - **Seek:** tap or drag the ruler, or drag the playhead, to go anywhere; arrow keys step through it. **Zoom** and **Fit** change how much shows.
  - **Change timing by dragging:** drag a line to move it later (a striped pause shows before it), drag its ends to change how long it stays, drag a character's or picture's bar to change when it comes in, drag the dotted lines inside a bar to change how long it takes to come in or go out, and drag ◆ markers to move a change. Tap anything to jump there and open that step.
- **Timing on every step** (⏱ Timing, at the bottom of each step):
  - Lines and narration: pause before, how long it stays on screen, how long the text takes to appear, and how it appears.
  - Title cards, choices, the end and pictures that pause: pause before and time on screen. The title screen's time is in Look.
  - Show and hide someone: start partway through the next line (Starts after), how long they take to come in or go out, and how (slide, fade, pop, rise or straight away).
  - Backgrounds: when, and how long the transition takes. Pictures: when, and how long they take to come in and go out. Effects: when, and how long. Sounds and music: when.
  - **Back to automatic** clears it. Time on screen is used when the story plays by itself (Watch, the video); when you tap through, a line waits for your tap. Pauses, delays and in/out times work everywhere, including the playable file.
- **Video:** MP4, WebM or GIF of the video path.
  - **File size:** picture size (full down to 640 × 360), how much detail it keeps (Best look, Balanced, Small, Smallest), smoothness (30, 24 or 15 frames a second) and sound quality, with an estimate of the size before you start.
  - **Aim for a size:** type a size in MB and it records to fit. **Pick size and smoothness for me** chooses the picture size and frame rate that look cleanest at that size. If a recording lands a little over, **Make it again** aims lower.
  - **GIF:** half, a third or a quarter size, 12, 8 or 5 frames a second, and 256 down to 32 colors.
  - Your choices are remembered for next time.
- **Playable file:** one HTML file with the whole story and its pictures, GIFs, videos and sounds inside. It opens in any browser on any device, with working choices, a restart button and full screen.
- **Projects** save as files with the pictures, GIFs, videos and sounds included; work is also kept in the browser.

---

## Motion Comic

Panels appear one by one, then their bubbles, with effects to make the big moments land.

### Pages and panels
- **Pages** are rows of one to three panels. A row's height is a slider; a panel's width share is in its settings. Panels appear left to right, row by row.
- **Each panel** has a background (your drawing or photo, or a drawn scene: street, sky, room, dusk, dark or a flat color) with a focus point, zoom and an optional slow push-in, plus **pictures on top**: any PNGs with see-through backgrounds (characters, props) placed and sized over the background. They pop, slide, drop or fade in one after another, flipped if you like.
- **Comes in:** pop, slide, fade, hard cut (with a white flash), wipe or zoom. Bubbles follow, or come first with the picture after.

### Bubbles
- Speech, thought (a cloud with a trail), shout (jagged), caption (a box) and whisper (dashed), in three sizes, placed with sliders, with the tail pointing where you say. A bubble can belong to a character, whose color dot shows on it.

### Effects
- Per panel, each with a "when" slider: a sound word (big outlined lettering in your color and size), speed lines from a point, motion streaks, an impact burst, a cut in (the camera zooms into the panel), shake, flash and a dramatic halftone tone.

### Reading
- **Scrolls down** like a webtoon: a tall 1080 × 1920 video, with the camera gliding down to keep each new panel in view.
- **Page by page** like a book: 3:4 pages that fit the screen, with a cut to the next page.
- White, paper or black page; thick ink, thin or no borders; slow, normal or fast pace; pops, hits and page-turn sounds; a title card and a "To be continued" card.

### Export
- **Video:** MP4, WebM or GIF.
- **Still picture:** the whole strip as one tall PNG for posting as a webtoon, or the current page in book mode.
- Projects save as files with the pictures included; work is also kept in the browser.

---

## Metadata Scrubber

Removes everything from a photo or video except the picture and sound themselves, then saves it under a new random name.

### What it removes
- **AI image data:** prompts, undesired content, seed, model and every generation setting from NovelAI, Stable Diffusion and ComfyUI.
- **NovelAI's hidden copy:** the copy of the settings NovelAI hides inside the image's transparency layer.
- **Camera and file data:** EXIF details (camera, date, **GPS location**), XMP, color profiles, Photoshop info, comments and Content Credentials.
- **The original file name.**
- **Videos (MP4 and MOV from phones):** the GPS location, phone make and model, software, and other details. The recording date can go too if you tick it. Picture and sound are left exactly as they were, with no re-recording, so there's no quality loss and it's quick even for big files.

### How it works
- **Adding files:** drop in as many PNG, JPG or WebP images and MP4 or MOV videos as you like, or pick or paste them.
- **What it found:** each image shows what was in the original (with copy buttons for the prompt and seed). The new file is checked again to confirm nothing is left.
- **Format:** save in the same format, or as PNG, JPG or WebP, with a quality slider.
- **Size limit (optional):** keep every image under a size you pick (for example, 1 MB). Quality steps down first, then the size, until it fits.
- **New names:** random letters or photo-style names (like `IMG_20261006_142233`). Edit any name or roll new ones.
- **Pixel shuffle (optional):** scrambles the invisible lowest bit of every pixel to wipe data other tools hide in the pixels themselves. It turns on automatically when hidden pixel data is found.
- **Download:** one at a time, or all at once as a ZIP.

---

## Caption Maker

Puts words on a picture: a caption, a line of dialogue, a speech bubble or a title. Open a picture (or drop or paste one), or start on a blank canvas in a color or see-through.

### Speakers and scripts
- **Speakers:** give a character a look once (font, colors, bubble, outline, which way the tail points), then pick them under **Speaker** for any text. **+ New speaker from this text** saves the look you made. If you change one of their bubbles, **Update Mina everywhere** puts that look on every bubble she says, on every picture (or **Back to Mina's look**). Rename or remove them under Manage speakers; they're kept in the browser.
- **Paste a script:** one line per bubble. `MINA: You came.` goes to Mina; a line with no name is a caption; `---` moves on to the next picture. New names become new speakers (each with their own border color), long lines are wrapped, and the lines are laid out top to bottom with speakers on alternating sides, without overlapping. Start on this picture or the first, keep or replace the text that's there, and keep bubbles off faces. Extra sections add copies of the last picture for you to swap.

### Styling single words
- Select words in the text box, then **B**, **I**, **A+** (bigger), **A−** (smaller), **Color** or **Clear**. Ctrl+B and Ctrl+I work too, and with nothing selected they style the word the cursor is in. In the text box styled words show as `[b]…[/b]`, `[i]…[/i]`, `[big]…[/big]`, `[small]…[/small]` and `[c=#FF3355]…[/c]`; you can type those too. Works on curved text, with outlines, shadow, glow and 3D.

### Placement
- **Snap to guides:** while dragging, text snaps to the middle, the safe margin and the edges and centers of other text, with a line showing what it snapped to.
- **Keep inside a safe margin:** text can't be dragged off the edge.
- **Move text off faces** (this picture, or every picture): an on-device face finder looks for faces and moves any text covering one to the nearest free spot. Bubble tails keep pointing where they did. The first time it gets the face finder (about 14 MB), then it works offline in the app.

### A set of pictures
- **Several pictures in one project**, each with its own text: **+ Add pictures** (or add several at once, or drop them). Each new picture starts with a text in the current look, ready to type.
- **The picture box:** under the picture you're editing, every picture in the project shows small in a big box that scrolls up and down, 15 to 20 at a time. Tap one to work on it. **Small**, **Medium** or **Large** changes how big they show, and you can pull the box's corner to make it taller. Drag a small picture to move it, or use ◀ ▶ for the one you're on.
- **Copy text between pictures:** pick a text, then **Copy this text to…** every other picture or one of them (it keeps its place and look), or copy all the text on a picture to all the others. Ctrl+C a text, switch pictures, Ctrl+V works too.
- **Duplicate** or **Remove** the picture you're on. Undo works per picture.
- **Pick several pictures** with the box on each one (or Shift-click, or **Pick all**), then **Remove**, **Duplicate** or **Clear** them all at once.
- **Save all** one after another, **Save all as ZIP**, **Save as one tall picture** (every picture stacked top to bottom with the gap you choose, for posting a whole strip), or **Share all** on phones.
- **File name** (in Save): type a name and every picture is saved numbered in order, `chapter 1-01.png`, `chapter 1-02.png` and so on, in Save all, the ZIP (named `chapter 1.zip`) and Save picture (which uses that picture's number). Put `#` where the number should go (`page # final` → `page 01 final`), and **Start at** another number if you like. Leave it empty to name them after the pictures you opened.

### Pictures on top (props and expressions)
- **+ Picture on top** puts a picture on top of the one you're working on: a prop, a face, an expression, a sticker. It isn't added to your set of pictures. See-through PNGs keep their see-through parts; big pictures are made smaller (up to 2000 pixels).
- Move it, resize it from the corner and turn it on the picture, like text. Its own settings: size, see-through, and flip across or upside down; shadows, glows, outlines and the rest are under Effects.
- **Layer:** **Under the text** (the start for new ones) keeps it over the picture but below every text, so captions and bubbles stay on top. **Over the text** lets ▲ ▼ put it in front of or behind each text.
- **Shape** (a fold-out, like **Bubble around it** and **Swap for**): crop it to a circle, rounded corners, a square, a heart, a star, a hexagon or a diamond, with **Zoom in**, **Picture across / up and down** to choose what shows inside, and a border in any color.
- **Bubble around it:** a thought bubble, speech bubble, round bubble, shout, rounded box or box, with its own color, how solid it is, room around the picture, a border, and a tail you point with the yellow dot (a character thinking of something, say).
- **Props and expressions:** everything you add waits in a tray under the picture to use again on any picture (tap it). Add several at once (or drop them on the tray) to fill the tray without placing them. ✕ takes one out of the tray; it stays on the pictures it's already on.
- **Swap for:** with a picture on top picked, tap another prop to swap it in, in the same place, size, shape and bubble. Handy for changing a character's expression.
- Copy it to other pictures like text (Ctrl+C, Ctrl+V, or Copy this text to…). The tray is kept in the browser and in project files.

### Filters (for the picture and pictures on top)
- A **Filters** section changes the picture itself, before its effects. **+ Add a filter…** has them in groups:
  - **Fix and adjust:** Auto levels, Auto contrast, Auto white balance, and Brightness, contrast and color (saturation, hue, warm or cool).
  - **Clean up:** Erase white paper (takes the paper out of a scanned drawing so only the lines are left), Remove white matte, Remove black matte.
  - **Style:** Vignette, Remove vignette, Chromatic aberration, Emboss, Solarize, Halftone (black or colored dots), Crystals (Voronoi), Black and white dither, Web-safe dither, Pixelate.
  - **Distort:** Twirl, Pinch / Punch, Spherical, Ripple, Lens distortion, Shear, Mirror, Rectangular to polar, Polar to rectangular.
  - **Blur:** Average, Gaussian, Box, Motion, Radial (spin), Zoom, Lens, Diffuse glow, Depth of field (tilt-shift), Maximum and Minimum.
- Added filters are listed in the order they run; tap one's name for its settings (one open at a time), untick it to compare, ▲ ▼ to change the order, ✕ to remove it. Sizes are measured on the picture, so they look the same on a small or big picture. Undo, reloads and project files keep them.

### Effects (for the picture and pictures on top)
- An **Effects** section like an image editor's layer effects, for the picture you're working on or for a picture on top (switch with **Effects on**): **Bevel / Emboss**, **Outline** (outside, center or inside), **3D**, **Inner shadow**, **Inner glow**, **Color overlay**, **Gradient overlay** (linear or radial, with scale, angle and position), **Outer glow**, **Outer shadow** and **Blur**.
- **+ Add an effect…** adds one; the ones you've added are listed with a tick to turn them off, and tapping a name opens its settings. Most have a **blend mode** (Normal, Multiply, Screen, Overlay, Soft light and the rest) and an opacity. **+** adds another outline, inner shadow, color or gradient overlay, or outer shadow; ✕ removes one.
- Under **More**: **Fill** fades the picture itself but keeps its effects (an outline with nothing inside, say). **Effects grow and shrink with the picture** keeps them in proportion when you resize a picture on top.
- They show in the saved pictures, the picture box and project files, and undo covers them. A dark **Inner glow** set to Multiply on the picture behind makes a vignette.

### Projects
- **Save project** keeps everything in one file to finish later: the pictures, all their text, your speakers and saved looks, and any of your own fonts the text uses. **Open project** (or drop the file on the page) brings it all back, on this device or another one. The last project you worked on is also kept in the browser.

### Text
- **As many pieces of text as you like.** Tap one on the picture to pick it, double-tap to type. **+ Text** adds another in the same look.
- **Several at once:** Shift-click (or Ctrl-click) text on the picture or in the list, or turn on **Select** and tap them (easier on a phone). **All** (or Ctrl+A) picks every text on the picture. Then **Delete** removes them all, dragging one moves them together, and arrow keys nudge them all. Tap an empty spot to go back to one.
- **On the picture:** drag to move (it snaps to the middle), pull the square corner to resize, turn it with the round handle (it snaps to 0°, 45° and 90°), and drag the yellow dot to point a bubble's tail. Arrow keys nudge it.
- **Undo and redo** (↶ ↷, or Ctrl+Z).

### Settings
- Every section (Looks, Font, Color, Outline, Shadow and glow, 3D and curve, Box and bubble, Size and place, Picture, Save) folds open and shut, with a note on closed ones saying what's set ("speech bubble", "two outlines"). **Open all** and **Close all** at the top; which ones are open is remembered.

### Looks
- One tap for a whole style. Your words and where they are stay put.
- **Save this look** keeps your own styles, for the next caption in the same style. Only your looks show. ✕ deletes one, after asking first.
- **Show 21 examples** opens the ready-made ones (Meme, Subtitle, Social, Speech, Round bubble, Thought, Shout, Comic caption, Manga, Sticker, Neon, Retro 3D, Gold, Horror, Note, Lower third, Banner, Pixel, Arched, Wedding and Typewriter); **Hide the examples** puts them away again, and the choice is remembered.

### Fonts
- About 55 free web fonts in groups (comic and manga, bold, handwriting, script, serif, clean, retro and pixel, spooky and fun), plus Impact, Arial, Georgia and Comic Sans from the device. Each shows your own words in the picker.
- **Your fonts:** add TTF, OTF or WOFF files with **+ Add font files** or **+ Add a folder** in the picker, or drop font files or a whole fonts folder anywhere on the page. They show their real names, stay in this browser for next time, and nothing is uploaded. Fonts you've licensed for your own use (like Segoe Print or RockStyle) belong here rather than in the site, which is public.
- **Favorites:** tap ☆ on any font in the picker (or the ☆ next to the font button) to keep it on your list. Favorites come first in every tab, have their own **★ Favorites** tab (the picker opens on it), and show as one-tap buttons under the font button. Until you have favorites, the fonts you used last show there instead (the **Recent** tab too). Kept in the browser.
- **On this computer:** in Chrome and Edge on a computer, **Use fonts on this computer** lists the fonts installed there (after you allow it) and uses them by name, with nothing copied. In other browsers, type a font's name. Installed fonts show only on devices that have them; to use a font everywhere, add its file.
- Size, bold, italic, all caps, line up left, middle or right, letter spacing and line spacing.

### Colors
- **Color picker:** tap any color (it shows its code) to open it: a color square and a hue strip, a hex code and R G B numbers, and the new color next to the old one.
- **Eyedroppers:** ⌖ **From the picture** takes a color from your picture; ⌖ **From the screen** takes one from anywhere on your screen (Chrome and Edge on a computer). **↺ Back to before** undoes the change.
- **Your colors:** press **+** to save the color you made. They show under every color setting (text, outline, shadow, glow, 3D, box, border, canvas) for one tap. **Edit** removes them. Also **Recent** colors and a palette. Kept in the browser.

### Effects
- **Fill:** one color, a two-color blend at any angle, or none (just the outline).
- **Outline**, and a **second outline** around it (the sticker look). **Shadow** with distance, softness, direction and strength. **Glow** in any color.
- **3D depth** in any direction and color. **Curve** the text into an arch or a dip.
- **Behind the text:** a box, rounded box, pill, a highlight behind each line, a speech bubble, a round bubble, a thought cloud, a shout burst, a tag, or a strip right across the picture, with its own color, how solid it is, room around the text and a border.

### Saving
- PNG, JPG or WebP (with quality), at full size or 2048 or 1080 pixels. A see-through canvas saves as a PNG with only your text, for putting on top of a video or another picture.
- **Save picture**, **Share** on phones, or **Copy** to paste it anywhere. Saved pictures carry no hidden data from the original.
- Your work, your looks and your fonts are kept in the browser. Save a project file too if you want a copy to keep or move to another device.

---

## SFX Maker

Type a sound effect and it becomes manga lettering (描き文字). Everything runs on the device; nothing is uploaded, and no AI is involved: the wobble and the ideas come from random numbers and set rules. Made for English and Japanese, with Korean and Chinese fonts too.

### The page
- The lettering is on the left with its tool bars (undo, Points, Liquify, the stage background, handles on or off, and below it: add a sound effect, auto pick, ideas, resets, Save PNG and Copy). Every setting is on the right: a strip of lettering styles, then folding cards in two columns (one on narrower screens). The lettering stays on screen while you scroll the settings (📌 unpins it).
- **Several sound effects on one page:** **+ Add SFX** adds another with its own words and settings; tap one on the page to edit it, ‹ › to step through them, **Delete** to remove one. Undo covers all of them.
- **SFX dictionary** (in Text): common sound effects in groups (impact, hits, rumble, motion, soft and cute, water, small sounds, gags, machines, eating, fire and electric), in Japanese and English. Tap one to use it; a lettering style is picked from the word. **✨ Auto pick** does the same for whatever you typed.
- **Page, underlay and script:** page size (wide to fit the screen, B5, SNS 4:5, square, 16:9); a picture of your own as an underlay (see Background below); and a **script**: one sound effect per line, `/` breaks it into lines, `|` adds a small note. **Place on page** turns each line into its own sound effect, spread down the page, with styles picked from the words and small differences between them.
- **Save** cuts to all the lettering, just the sound effect being edited, or the whole page.

### Text
- Type the sound effect; each line of text gets its own line of lettering. **Across** or **Down** (vertical writing, right to left).
- **Stretch long marks** draws ー (and -, ~) stretched along the line, as long as the **Long mark stretch** setting. Small kana (ッ, ゃ) are drawn smaller. **Add ゛** puts dakuten on every kana (ハハ → バババ).
- **Small note beside it** (添え字): a smaller word below, above, right or left of the lettering.

### The line
- The page is 1000 px tall and as wide as your screen has room for (1400 to 2600 px), so wide screens get a wide page. Letters sit on a curve. Drag ● at either end to move it; drag ◆ to bend it. Hold Shift while dragging an end to leave the bend where it is. **Reset line** straightens it.
- **Follow the curve** sets how much letters turn with it, from staying level to turning fully.
- **Tap a letter** to pick it, then drag it, turn it with ○ or resize it with □. Arrow keys nudge it (Shift for 10 px). Double-tap puts it back; **Reset letters** puts them all back.
- **Start over** (in the bar under the picture) clears the page and goes back to one “BOOM” in the Comic style, with the page, lettering and save settings as they start. It asks first, and Undo brings your work back. If you have an underlay picture, you choose whether to keep it; removing it can’t be undone.

### Reshaping letters
- **✒ Points:** tap a letter and its outline becomes points (traced from the drawn letter). Drag a point; double-tap a line to add one; double-tap a point to switch it between a corner (square) and smooth (round); Delete removes it. **Reset this letter** or **Reset all** goes back to the font's shape.
- **◎ Liquify:** a brush with **Push**, **Bloat**, **Pinch**, **Twirl ↻** and **Twirl ↺**, with brush size, strength and hardness; hold Alt to reverse. It works on every letter under the brush.
- Reshaped letters keep their new shape when you move, turn or resize them, and the SVG keeps them as paths. Undo covers every point and brush stroke.

### Background (underlay)
- **Open a picture** (or drop one on the page) to put a page, a panel or a photo behind the lettering, fit inside or filling the page, at any opacity. The lettering saves on its own, see-through, unless you tick **Save it with the lettering**, which saves the whole page with it (PNG, copy and SVG). The picture is kept in the browser.

### Lettering styles and fonts
- One tap for a style: Comic, Rounded, Brush, Marker, Pen, Lightning, Board, Negative, Spooky. A style picks a font for the language you typed and sets its outline, edges and wobble; change anything after.
- About 90 free fonts from Google Fonts in groups (Japanese, comic, bold, rounded, brush, pen, fun and retro, spooky, Korean and Chinese), shown in your own words. Japanese fonts cover English too.
- **Your fonts:** add TTF, OTF or WOFF files in the font picker. They stay in this browser and are shared with Caption Maker.

### Shape and wobble
- **The big three:** **Impact** (size, outline, growth), **Roughness** (wobble, rough edges, dry brush) and **Momentum** (lean, long-mark stretch, afterimages) each move several settings at once, on top of the detailed ones.
- **Wobble seed** with a dice: a new random wobble each time, kept so the same seed gives the same result.
- Letter size, spacing, follow the curve, lean, fan out, grow along (bigger or smaller toward the end), long mark stretch, and random wobble of angle, size and height per letter.
- **Squeeze the whole thing:** narrow at the top, bottom, left or right.

### Fill, outline, shadow, motion, edges
- **Fill:** a color, white, gray, halftone dots, dots fading across, line tone, outline only, or negative (white letters on a black shape). Dot spacing and darkness.
- **Outline:** thickness and color, around each letter or the whole word, sharp or rounded corners, and a second outline around the first.
- **Shadow:** drop shadow or extruded 3D, with direction, length and color.
- **Motion:** motion blur (width, copies, direction) and afterimages (gap, how many, fade, direction).
- **Edges:** clean, lightning (jagged bands) or torn; hand-drawn roughness, dry brush and haze.

### Ideas
- **🎲 Draw ideas:** a sheet of 12, 24 or 48 random variations (calmer, wilder or both). Tap one to use it; your words and line stay. **🧬 Mutate** makes 12 small variations of the current look, as different as you set.
- Undo (Ctrl+Z) and redo cover everything, including an idea you picked.

### Saving
- **Save PNG** (see-through or white, 1× to 4×, cut to the lettering or the whole page), **Save SVG** (the letters stay text, fonts from Google Fonts, your own fonts embedded by name), **Layered ZIP** (text, outline, shadow, afterimages and motion blur as separate PNGs for layers in Clip Studio or Photoshop), **Copy** to the clipboard, and **Copy link** (a link that carries the words and every setting).
- Halftone, edges and the squeeze only come out in PNG. Clip Studio drops SVG fills, so use PNG or the layered ZIP there.
- Your work is kept in the browser.

---

## Effect Lines

Manga effect lines and screentones (効果線・トーン), rebuilt after the Effect Lines & Screentone Generator by MIYADAIKU (Oyasumi Game Dev). Everything is drawn on the device from random numbers and set rules; nothing is uploaded.

### Types
27 types in five groups, each a small picture at the top right. Hover one for what it does.
- **Focus lines:** focus lines (always run past the edge), flash rays, black flash (a spiky white hole in solid black), urchin flash (a ring of needles, single to triple).
- **Effect lines:** speed lines, curved lines, wind, drop lines (with a dotted "breakup" at the tips), rain.
- **Cross-hatch:** cross-hatch (single to quadruple, flow, edge fade), hatch gradient (with solid black at the dark end), black edge (a black area dissolving into fine lines, cut by a line or a circle), rope hatch, rope hatch gradient and radial rope hatch (bundles that follow a flow; only the top bundle shows where they overlap).
- **Tones:** halftone (round, square or diamond dots), line tone, gradient (two densities and positions, round or line), 19 patterns (checker, diamonds, grid, lattice, hollow dots, stars, crosses, hexagons, kagome weave, hemp leaf, seigaiha waves, shippo circles, scales, arrow feathers, meander, bricks, random flowers, hearts, wavy lines), stipple, sand grain.
- **Mood:** sparkles, flowers (4 to 8 petals), hearts, petals, bubbles, snow.

### Shaping
- **Drag in the preview** to move the center of the types that have one; it can sit outside the frame. The **Center** sliders do the same.
- **Adjust** shows the sliders and choices for the picked type: count, inner radius, length, width and their variations, clustering, bend, taper, direction, band, scatter, wobble, stacking, flow, edge fade, waviness, crossing, coverage, gradient start / midpoint / end, and so on. **⟲ Default** puts them back.
- **🎲 New shape** keeps the settings and draws the same type with a new random seed (the same seed always gives the same shape). **🎲 All** rerolls every layer. Types without randomness say so.
- **Rotate all** (the hatching types) turns the drawing inside while the frame stays put.

### Layers
- **+ Add layer** stacks up to 8 effects, such as focus lines over a halftone, or a tone inside a black flash. Clicking a type changes the selected layer. The eye hides a layer; ▲ ▼ reorder; ✕ deletes.
- Each layer has its own **color** (black, white, red, blue, yellow or any color), **opacity**, and whether its **white areas** are cut out to transparent or filled white.

### Gacha
- **🎰 Gacha** fills the preview area with 4, 9 or 16 picks: new seeds with slightly varied settings (**Spread** low, mid or high; **Mix types** draws 70% from other types in the same group). Click one to load it into the selected layer. **🧬 Mutate current** keeps the shape and nudges the settings. **▦ Results** reopens the last picks.

### Preview and underlay
- The preview background can be a checkerboard, white or black. **Underlay…** (or drop / paste a picture) puts your art or a panel layout underneath so you can line up the focus point or match tone density; it is never saved.
- **Sharper preview** draws the preview at twice the size; turn it off if it feels slow.

### Save
- **Image size:** 16:9 (1920×1080), portrait 9:16, square 2048, social 4:5, B5 manuscript at 350 dpi, or any width and height from 64 to 8000 px. Saves at ½, 1× or 2× (capped at 8000 px on the long side).
- **Save PNG** (transparent, white or black background), **Save SVG** (halftones and patterns become SVG patterns, lines become shapes, cut-outs become masks), **ZIP by layer** (one PNG per layer plus the whole picture as PNG and SVG), or **Copy** to paste into Clip Studio Paint or a post.
- **Copy share link** puts the current settings in the page address so someone else can open the same picture.
- Settings stay in this browser. **Reset all settings** starts over.

---

## Panel Layouts

Manga and comic panel layouts (コマ割り) in batches, rebuilt after the Manga Panel Layout Generator by Oyasumi Game Dev. Everything is made on the device from random numbers and set rules; nothing is uploaded.

### Making a batch
- **Starting points:** Orderly / Dialogue (straight rows, more panels), Standard, Action (slanted, fewer and bigger panels, more bleeds) and Splash / Title page (one big panel, lots of bleed). Each one sets the sliders; move any slider to go your own way.
- **Format:** a manga page (B5), a social post (4:5) or a square. **Rows:** 1–2 up to 3–4. **Only layouts with … to … panels** keeps pages with that many panels.
- **Sliders:** slanted rows, slanted columns, bleed (panels that run off the page edge past the dotted inner frame), split panels, big panels and border width.
- **Reading:** right to left like Japanese manga or left to right like Western comics. Switching mirrors the same layouts, and the numbers show the reading order.
- **Seed:** the same seed and settings always give the same batch. Type `PL-2026#5` and press Enter to open the 5th page of batch PL-2026. **🎲 New batch** picks a new seed. 12, 24 or 48 pages at a time.

### Editing
- Click a page to open it large. **Drag a border** to move it; grab it near one end to tilt it. It stops before any panel gets too small.
- Click a panel to pick it (Shift for more) and press **Delete** to remove it; the panel next to it grows into the space. **Ctrl+Z** undoes; ◀ ▶ or the arrow keys go through the batch.
- Edits stay with the batch (and after a reload) as long as its seed and settings stay the same. Edited pages are marked in the grid.

### Mutate
- **🧬 Mutate from this** turns one layout into a batch of variations: borders moved and tilted, panels split or merged, bleeds changed. **Low**, **Medium** or **High** sets how far they go; High can add or remove a row. Straight rows (or columns) stay straight. #01 is always the layout you started from, and you can mutate a mutation.

### Saving
- **Save SVG** (vector lines) or **Save PNG** (2400 px tall, or 1200, 3600 or 4800), one page at a time, or the whole batch as a ZIP of PNGs or SVGs, named in order (`panels_PL-2026_01.png`…).
- **Background:** **Clear** leaves only the panel lines on a transparent picture, **White** or **Black** fills the page. **Lines** are Auto (white on black, black otherwise), black or white. **White inside the panels** keeps the panels white with black or clear gutters. The editor shows the saved look.
- The reading-order numbers and the inner frame guide are left out of saved files unless you tick them. **Copy picture** puts the PNG on the clipboard; **Copy link** carries one layout, edits included.
- In Clip Studio Paint: open the PNG as a guide and trace it with the Divide frame tool for masked panels, or use File › Import › Vector (Ver. 1.10 or later) for the SVG as lines.

---

## Bubble Maker

Manga speech and thought bubbles (吹き出し), made on the device from shapes and random numbers; nothing is uploaded.

### Styles
- The strip at the top: **Classic**, **Thought**, **Shout**, **Whisper**, **Shaky**, **Radio**, **Narration**, **Soft**, **Shoujo**, **Flowers**, **Pop**, **Echo**, **Horror**, **Flash** and **Tone**. A style sets the shape, tail, outline, fill, decorations and font; your words, place and size stay. Every setting can then be changed.
- **Shapes:** speech (oval), thought (bumps), shout (spikes), zigzag, flash (many small spikes), wobbly, whisper (dashed), rounded box, box, or no bubble (words only). **Hand-drawn wobble** roughens any shape. The spikes, bumps and wobble come from a random seed; ⚄ rolls a new one.

### Words
- Type the words; a new line starts a new line. **Across** or **Down** (vertical, for Japanese, with long marks and brackets turned). Size, line spacing, letter spacing and color.
- About 100 free fonts (a Dialogue group for easy reading, plus comic, bold, rounded, brush, pen, fun, spooky, Japanese, Korean and Chinese) and your own font files, kept in the browser and shared with Caption Maker and SFX Maker.
- The bubble **fits itself round the words** with as much room as you like, or untick that and set the width and height (dragging a corner does the same).

### Tails
- One tail, or a second one for two speakers. **Pointed**, **Curved** (with a curl) or **Thought bubbles**. Drag ● at the tip on the page to point it, or use the direction, length, width and curl sliders.

### Fill, outline and extras
- Fill color and opacity, with a dot, line or cross-hatch pattern. Outline color and thickness, a **double line** with a gap, or **dashed** for whispers.
- A drop shadow, and **decorations** round the bubble: hearts, stars, sparkles, flowers, bubbles, lines or drops, in any color, count and size.

### The page
- Several bubbles on one page: **+ Add bubble**, Duplicate, Delete, ▲ ▼ for the stacking order, ‹ › to switch, or tap one. Drag to move, □ to resize, ○ to turn. Arrow keys nudge, Delete removes, Ctrl+Z undoes, Ctrl+D duplicates.
- **🎲 Draw ideas** shows 12 random takes on the current bubble (styles, shapes and tails); **🧬 Mutate** makes small changes. Tap one to use it.
- **▦ Bubble sheet** fills the page with 6 to 16 bubbles in rows, empty or with sample words, in this style or a mix, ready to save see-through and cut up in your drawing app.
- Page sizes: wide, B5, 4:5, square or 16:9. An **underlay** picture (a panel layout from Panel Layouts, or your page) can sit behind the bubbles while you place them; choose whether it is kept in the saved picture.
- **Start over** clears the page (it asks first; Undo brings the work back).

### Saving
- **Save PNG**: everything cut to the edges, this bubble only, or the whole page, at 1×, 2× or 3×, with a **clear**, white or black background. **Each bubble (ZIP)** saves every bubble as its own see-through PNG.
- **Save SVG** keeps the shapes as paths and the words as text (the font by name). **Copy** puts the picture on the clipboard; **Share link** carries the whole page.

---

## Watermark

Puts your name or logo on your photos. Add one photo or a whole batch; every photo gets the same watermark in the same spot, sized to match.

### Your watermark
- **Words:** one or more lines, with quick buttons for ©, the year and @.
- **Logo:** add a picture (a PNG with a see-through background looks best), before or above the words, in its own colors or in the text color.
- **Style:** seven fonts, size, color, how see-through it is, a tilt, and a shadow, outline, box or band across the photo behind it.

### Presets
- **Ready-made looks:** corner signature, small copyright, label, handwritten, center stamp, proof band, and tiled all over (faint or strong). Presets change only the look and the spot; your words and logo stay.
- **My watermarks:** save your words, logo and look under a name, like "Instagram" or "Client proofs", and use them again with one tap. They're kept in the browser.

### Position
- **Nine spots** (corners, edges, middle) with a distance from the edge, or drag it anywhere in the preview, or tap where you want it.
- **Just this photo:** tick "Dragging moves it on this photo only" to nudge the mark off a face or a detail on one photo. The others keep their spot.
- **Tiled:** repeat it across the whole photo at an angle, with your own spacing, so it can't be cropped out.

### Saving
- **Save as** the same format as each photo, or JPG, PNG or WebP, with a quality slider.
- **Size:** keep each photo's size or make long ones 4K, 2048 or 1080 pixels.
- **Names:** random (like the other tools) or your file names with `-wm` added.
- **Clean copies:** saved photos have none of the original's hidden data (no location, camera details or prompts).
- **Save** one photo, all of them, or a ZIP, or share them straight from your phone.

For videos, add your logo or text as a layer in [Video Layers](#video-layers).

---

## Background Remover

Takes the background out of photos and videos. Add one file or a whole batch; each one is done on your device, one after another.

### What to keep
- **People:** faces, bodies and hair.
- **People and animals:** also cats, dogs, horses, birds and farm animals.
- **Anything it knows:** also cars, bikes, furniture, plants, bottles and screens.
- **Plain background or green screen:** no AI, just color, found by itself. On a photo, anything on one even color (a logo, a drawing, a product on white) comes out clean, including small text; tick **Also remove it inside shapes** to clear the holes in letters and gaps too. On a video, the screen color is found from the edges and keyed out of every frame, like a green screen.
- **Remove a color:** like a chroma key in a video editor. Pick the color (green, blue, white, black, any color, or tap it in the picture with **Pick from the picture**) and it turns see-through wherever it shows up. **How much to remove**, **Soft edge** and **Clean up colored edges** (takes the green or blue tint off hair and edges).

On a plain wall or studio paper, the AI choices also check the background's color, so the edge follows the real outline and the light or dark rim around it is taken out. "Plain background" and "Remove a color" work inside Claude too.

### Edges and touch-ups
- **Tighter or looser** (AI choices) and **Soft edge** sliders, and **Steadier edges** for videos so the outline doesn't flicker.
- **Remove small leftover bits and fill pinholes** (on by default).
- **Touch-up brush (photos):** Erase takes more away, Keep brings parts back. Removed parts show faintly while you paint. Undo or clear the strokes; each photo keeps its own.
- **Hold to see the original** to compare. Videos have play and a bar to move through them.

### Background and saving
- **Behind it:** see-through, a color, a blurred copy of the photo or video, or **a picture** of your own.
- **Sticker outline** in any color and width, and for photos **Crop to what's kept** with your own space around it.
- **Photos** save as PNG or WebP (see-through) or JPG, with an optional size limit.
- **Videos** save as MP4 or WebM, at their own size or 1280 or 720, with their sound. A see-through video is saved as WebM, which keeps the see-through parts (it plays in Chrome and on Android, and editors that take WebM can lay it over other clips). Saving does every frame first for the AI choices, then the video plays through once while it records, so keep the tab in front.
- **Names:** random, or your names with `-nobg`. Save one, all, or a ZIP, or share from your phone. Saved copies have none of the original's hidden data.

The AI is the same on-device background remover Video Layers uses (Google's MediaPipe, in `vendor/mediapipe/`). It downloads about 14 MB the first time and is kept for next time, including offline. Video Layers keeps its own **Remove background** and **Green screen** for layers inside a bigger edit.

---

## Video Layers

Puts pictures, videos, text, music and your voice together and makes a new video or GIF. The first picture or video you add fills the frame. Anything after it goes on top as an overlay, and each layer gets its own bar on the timeline.

### Pictures and videos
- **Move and resize:**
  - Drag a layer to move it. It snaps to the edges and middle of the video and to other layers.
  - Drag a corner to resize (the shape is kept unless you hold Shift).
  - Untick **Keep its shape** to stretch it with the side handles.
- **Exact numbers:** type the position, width and height in pixels.
- **Fit, Fill or Stretch** to the whole video, or snap the layer to any of 9 spots.
- **Crop:**
  - Open the crop tool and drag the corners or edges, freely or locked to a shape (1:1, 4:5, 9:16, 16:9, 4:3, 3:4, the video's shape, or another layer's shape).
  - There are also quick-crop buttons and a slider for each side.
  - Cropping keeps what's left the same size and in the same place.
- **Turn and flip:** a rotate handle (snaps to 45° steps), 90° buttons, mirror and upside down.
- **Match another layer:**
  - Same width, same height, fit inside it, or cover it.
  - **Crop to match** or **Stretch to match** puts it exactly on top of the other layer at the same size and shape.
  - Or place it on any of 9 spots of that layer, such as a picture in the corner of the video.
- **Look:**
  - Opacity, and square, rounded or circle shape.
  - A border, and a drop shadow that follows the outline of see-through PNGs.
- **Blend:** **Screen** hides black backgrounds; **Multiply** hides white ones.
- **Color:**
  - Filters: B&W, Vintage, Warm, Cool, Vivid, Faded, Noir, Dramatic and Dreamy.
  - Sliders for brightness, contrast, saturation, warmth, hue, black and white, and dark edges.
- **Blur and mosaic:** blur a whole layer, or turn it into big pixels (mosaic). Both work in every browser, Safari included.
- **Slow movement:** a slow zoom in or out, or a drift in any direction, over the time the layer shows.
- **Remove background (automatic):**
  - Finds the people in a video or picture and hides everything else, with no green screen needed. An AI model does this on your device; nothing is uploaded.
  - **Keep:** People, or People and animals (also cats, dogs, horses, sheep, cows and birds; slower).
  - **Background:** remove it so the layers underneath show through, or blur it like a phone's portrait mode.
  - Sliders for a tighter or looser edge, soft edges, and steadier edges so the outline doesn't flicker.
  - **Plain backgrounds** (a white wall, studio paper or any even color): the edge follows the background's color instead of the model's rough outline. This keeps arms and hair the model misses, drops background showing between arms and soft shadows on the wall, and leaves no light rim around the person. It's on by default; turn off **Sharper edges on a plain background** if it keeps something it shouldn't.
  - The first time, it downloads about 13 MB (more for People and animals). After that it's kept on your device and works offline in the app.
  - Before a video or GIF is saved, every frame is done once ahead of time, so the result plays smoothly. This takes a little while for long videos.
- **Green screen:**
  - Removes one color so the layers underneath show through. The screen color is guessed from the edges, or picked by tapping the background in the preview.
  - Sliders for how much to remove, soft edges and cleaning up colored edges.
  - Also works on pictures with a flat background.

### Video and sound
- **Timeline:** trim the start and end by dragging the bar ends or with sliders.
- **Speed:** ¼× up to 4×.
- **Slow motion:**
  - For the whole clip, pick ½× or ¼× under Speed.
  - To slow down just a moment, put the playhead where it starts and pick ½ or ¼ speed for 1, 2 or 3 seconds. The clip is cut there, that part plays slower, and everything after it moves later to make room.
  - It looks smoothest with videos filmed at 60 frames a second or in a phone's slo-mo mode.
- **When a video ends:** it can disappear, freeze on the last frame, or loop.
- **Sound:** volume, mute, and sound fade in and out for each video and music track.
- **Split:** cuts any layer in two at the playhead (keyboard: S).

### Effects
- **✦ Effects** under the preview (for a video or picture) has everything below in one menu.
- **Freeze frame:** holds the picture at the playhead still for 1, 2 or 3 seconds (optionally with a camera-flash), then the clip carries on. Everything after it moves later to make room.
- **Camera shake** (Motion tab): Handheld sways gently, Strong rumbles, and **A jolt at the start** shakes hard and settles. Videos and pictures zoom in a little so their edges never show; text shakes as a whole.
- **Glitch** (Motion tab): red and cyan color fringes, with torn, flickering lines now and then. Works on text too.
- To shake or glitch just a moment, split the layer first.
- **Blur or mosaic a spot:** a box that blurs, pixelates or covers with a solid color whatever is underneath it. Use it to hide a face, a name or a number plate.
  - Drag it into place and pull its corners to size it. Shapes: rectangle, rounded or oval, with soft edges if you like.
  - **Cover all** stretches it over the whole video, for example to blur everything for a few seconds.
  - It has its own bar on the timeline, so it can show for just part of the video.
  - **Follow a face:** put the spot over a face and tap **◉ Follow face**. An on-device face finder goes through the video a few times a second and adds keyframes so the spot stays on that face. **Blur a face** in the Effects menu does both in one go. Where the face can't be seen for a moment, the spot glides between the places it was found. Drag it at any moment afterwards to fix it. The first time it downloads about 1 MB, then it works offline in the app.
  - Or add keyframes yourself (Motion tab) so the spot follows anything else that moves.
  - It only changes the layers below it in the list, so keep it at the top to cover captions too.

### Text overlays
- **Styles:** 10 one-tap styles: Caption, Highlight, Meme, Title, Lower third, Subtitle, Neon, Sticky note, News bar and Typewriter.
- **Fonts:** 13 of them, including Clean, Wide, Bold, Tall, Serif, Elegant, Marker, Handwriting, Script, Comic, Rounded, Typewriter and Mono.
- **Text settings:** size, color, alignment, italic, ALL CAPS, letter and line spacing, and wrap width (drag the side handles).
- **Outline and shadow:** an outline in any color and thickness, and a soft, hard or glowing shadow.
- **Backgrounds:** a box, a box behind each line (TikTok-style) or a full-width bar, in any color and opacity.
- **Shortcut:** double-click text in the preview to edit it.

### Animation (every layer)
- **Entrances and exits:** fade, pop, zoom, wipe, blur, glitch, flash, or slide from or to any side.
- **Transitions between clips** (Timing tab, or ✦ Effects): crossfade, dip to black, flash, push, wipe, zoom, blur or glitch into the video or picture that comes next. The next clip moves earlier so the two overlap while it plays, and everything after it moves along. Choose the length (0.2 to 2 seconds). The timeline shows a striped end on a clip that has one.
- **For text only:** typewriter and word by word.

### Motion paths (keyframes)
- **Make anything move:** a sticker or text can travel along a path, grow, turn and fade over time.
- **How:** put the playhead where the motion starts and tap **Keyframe** (keyboard: K). Then move the playhead later and drag, resize or turn the layer; a new keyframe is added for you.
- **Path preview:** the path shows as a yellow line in the preview. Keyframes show as diamonds on the timeline; tap one to jump to it or drag it to change when it happens.
- **Easing:** ease in and out, or a steady speed.
- **Quick moves:** left to right, right to left, up from the bottom, grow in, spin and float.

### Layouts
- **One tap** arranges the first two pictures or videos: top and bottom, side by side, reaction in the corner, picture in picture, face in a circle, or big and small.
- Each one is cropped to fill its spot, and **Swap** switches which goes where.

### Voiceover
- **Record your voice** with the microphone while the video plays from the playhead. It becomes its own sound layer you can move, trim and fade.
- The video's sound is muted while you record unless you choose to hear it (use headphones).

### Video size
- Found under **Size & layout**.
- **Drag to resize:** tap **⤢ Resize** on the preview, then drag any edge or corner of the video. Layers keep their size and place, so dragging an edge out adds space (filled by the blurred or solid background) and dragging it in trims. It snaps to 9:16, 1:1, 4:5, 16:9 and other common shapes, and to the edges of the bottom layer. **Fit the bottom layer** makes the video exactly the size of the bottom picture or video.
- **Exact pixels:** type any width and height (up to 4096) and the video is exactly that size. A link button keeps the shape while you type if you want it to.
- **Quick sizes:** Auto (follows the bottom layer), 9:16, 1:1, 4:5, 16:9, 4:3, 3:4, and a button to turn it sideways.
- **Stretch to this size:** squeezes the main video to fill any size you pick.
- **Empty space** (around a video that doesn't fill the frame):
  - **Blurred video:** a blurred, darker copy of the bottom layer.
  - **Stretched edges:** the colors along the edge of the video are stretched out and softened, so the picture seems to carry on.
  - **Mirror:** the video reflected into the space, softened and a little darker.
  - **Gradient:** two colors blending top to bottom, left to right, corner to corner or from the middle. **Match the video's colors** picks them from the edges of the bottom layer.
  - **Color:** one flat color.

### Editing comforts
- **Undo and redo:** Ctrl+Z and Ctrl+Shift+Z.
- **Quick-edit bar** under the preview: Crop, Fit, Fill, Stretch, Flip, 90°, Remove background, Green screen, Keyframe, Split and Duplicate.
- **Keyboard:** arrow keys nudge (Shift for bigger steps), Delete removes, Ctrl+D duplicates, K adds a keyframe, Space plays and pauses.
- **Save frame:** saves the picture at the playhead as a PNG or JPG. A PNG can have a see-through background, which turns a cut-out person into a sticker.

### Export
- **Formats:** **MP4** or **WebM**, with sound, at best quality, half size or under a size limit. Or a looping **GIF** (no sound), standard or under a size limit.
- **Recording runs in real time,** so a 20-second video takes about 20 seconds. Keep the tab in front while it records. A GIF steps through frame by frame instead.

---

## Outfit Tags

Reads the outfit in a photo or a piece of anime art and turns it into tags and prompts for AI image generators such as Illustrious, NoobAI, Pony, NovelAI and Flux. Tabs under the title switch between the tags, a map of the picture, new outfit ideas, the catalog and settings; the photo panel stays put. **Unlike the other tools, it sends the photo you pick to an AI model to read it.**

### Reading a photo
- **Up to 5 at once:** drop, pick or paste them, or share them from your gallery. They're read one after another, and photo tabs above the tags switch between them.
- **Who reads it:**
  - On the website: Claude, with your own Anthropic API key, or any OpenAI-compatible model. The key stays in your browser and goes only to that provider. Reading one photo costs about 5 to 10 cents on Claude Opus, billed to the key's account.
  - Inside Claude: your Claude account, with no key needed. The first read asks you to allow it.
- **Tags by garment:** each piece of clothing gets its own group of Danbooru tags, with how sure it is, plus hair, face, style and framing.
- **The whole picture, if you want it:** choose "Everything" to also get background, composition, lighting, colors and visual aesthetic as their own groups, and untick the ones you don't need.
- **Map:** the picture with a label pointing at the hair and each garment. The positions are the model's guess, so drag a dot if one is off; on phones the dots are numbered instead.
- **Characters, series and named outfits:** fictional characters, their series and named outfits (like a particular school's uniform), with what gave them away. It never identifies real people; for cosplay it names the character being worn.
- **Checked on Danbooru** (website only): name order is fixed (`miku_hatsune` becomes `hatsune_miku`), near misses are corrected, and names Danbooru doesn't know are flagged and left out of the prompt until you put them back.

### Prompts
- **Generators:** ready-made settings for Illustrious XL, NoobAI XL, Pony V6, Animagine XL 4, NovelAI V4.5 and Flux add the right quality words, negative prompt and weight style. You can edit each one.
- **Formats:** tags with underscores or spaces, tags weighted by how sure it is, tags plus one sentence about layering and fit, or plain sentences for models that read them. After you edit the tags, **Rewrite it** updates the sentence.
- **Copy:** the whole prompt, the negative prompt, just the outfit, or any one group. Tap a tag to open its Danbooru wiki page; **×** leaves it out of the prompt.

### Your outfits
- **Catalog:** every read is kept with a thumbnail and where it came from. Name it, add labels and notes, star it, mark it "to try" or "done", and search everything. Export and import it to move it between devices.
- **Three new outfits:** three fresh takes on any outfit (a restyle, a different genre, a different season), or your own direction like "make it winter".
- **Remix:** delete or add tags, swap in a garment from another saved outfit, add or remove pieces, and save it as a copy.
- **Check tags:** fixes common misspellings and, on the website, shows how often each tag is used on Danbooru.

With the extension installed, this page and the extension share one catalog (and the page can use the extension's API key), so an outfit read from the right-click menu shows up here and the other way round. Before that, each keeps its own. A Chrome and Brave extension that reads any image from the right-click menu lives in the [Outfit-Idenitfy](https://github.com/lopxfi/Outfit-Idenitfy) repository. This page is built from that repository's code with its `build_phototools.py`.

---

## What's in the files you save

Nothing that points back to you or your originals:
- **Pictures** (PNG and JPG) are drawn fresh, so no location, camera, phone or date from your photos comes along. JPGs also have the browser's color profile removed, leaving only the picture.
- **Videos** (WebM and MP4) are recorded fresh too. The browser's name, any titles, handler names and creation dates are blanked out.
- **GIFs** carry nothing but the loop setting.
- **File names** use a random code (like `story-rmwhbr.png` or `split-jmss3w-1-of-3.jpg`), never your original file name or the time. In Chat Reel you can type your own name instead.
- **ZIP files** date every file 1 January 1980, so they don't record when you made them.
- **Project files** (`.json`) are for your own use: they hold what you typed, your photos (already cleaned) and when you saved. Chat Reel's include any sound files you added exactly as they were.

## On a phone

The desktop layout stays as it is. On a phone (or a tablet held upright) the tools rearrange themselves:
- **Video Layers:**
  - The preview stays at the top while you scroll, and tabs along the bottom switch between **Layers**, **Edit**, **Timeline** and **Size**.
  - Under the preview, a row holds the main quick edits; **More ▾** has the rest.
  - **Press and hold** a layer in the preview, on the timeline or in the layer list for its menu: settings, crop, duplicate, split, bring forward, send back, hide or delete.
  - Settings are grouped into sections you tap to open, so the list stays short.
  - **⋯** next to the playback buttons has Back to the start, Loop, Mute and a bigger preview.
  - **Seek bar:** a big bar under the preview moves the playhead. Drag anywhere on it; ‹ and › step one frame at a time (hold to keep going). The selected layer's stretch of time shows as a band on it.
  - On the timeline, the playhead itself can be grabbed and dragged.
  - Picking a layer on the preview opens its settings. In the layer list, tap a picked layer again to edit it.
- **Chat Reel:** the preview stays at the top, and tabs along the bottom switch between **Chat** (the messages), **Message**, **Look**, **Sound** and **Timeline**. The ✎ on a message opens its settings. The same seek bar sits under the preview, with a tick where each message arrives, and the playhead on the timeline can be dragged.
- **Photo Frame Studio:** the preview stays in view while you edit the words, and **⤢ Bigger** makes it larger.
- **All of them:**
  - The preview shrinks while you type, so the keyboard doesn't cover the field.
  - Fields use a text size that phones don't zoom into.
  - Buttons are bigger to tap.
  - Long settings fold into sections.

## Install it as an app (works offline)

- **Android (Chrome):** open the site, tap **⋮** and choose **Install app** or **Add to Home screen**.
- **iPhone (Safari):** open the site, tap **Share** and choose **Add to Home Screen**.
- **Computer (Chrome or Edge):** click the install icon in the address bar, or use **Install app** on the start page.

Open each tool once while you're online so everything, fonts included, is saved for offline use. The background remover in Video Layers is saved the first time you use it. Updates download on their own the next time you open the app online.

## Sharing into the tools

- **Android:** after installing the app, open a photo, video or sound in your gallery (or any app), tap **Share** and choose **Photo Tools**. A page shows what you shared and which tools can take it: the Splitter and Outfit Tags for photos, Frame Studio and the Scrubber for photos and videos, Video Layers and Chat Reel for all three.
- **iPhone:** iOS doesn't let web apps appear in the Share menu. Use **Add photo** in any tool, which opens your photo library.
- **Between tools:** after exporting in Photo Frame Studio, tap **Split for X** or **Use in Video Layers**; after exporting in Chat Reel, tap **Use in Video Layers**. The result is carried straight over. This works on the website and in the installed app.

## Browser notes

- **Chrome and Edge** support everything, including video export with sound.
- **Safari:**
  - Video export depends on the Safari version; MP4 is the format to try.
  - Color filters in Video Layers need a recent version. Blur and mosaic work on any version.
- **GIFs** are silent and limited to 256 colors.
- **Voiceover** needs microphone permission. The browser asks the first time.

## Files

| File | What it is |
|---|---|
| `index.html` | Start page with links to every tool and the install button |
| `share.html` | The page that opens when you share files to the app, to pick a tool |
| `photo-frame-studio.html` | Photo Frame Studio |
| `photo-splitter.html` | Photo Splitter |
| `chat-reel.html` | Chat Reel |
| `metadata-scrubber.html` | Metadata Scrubber |
| `watermark.html` | Watermark |
| `caption-maker.html` | Caption Maker |
| `sfx-maker.html` | SFX Maker |
| `effect-lines.html` | Effect Lines |
| `panel-layouts.html` | Panel Layouts |
| `bubble-maker.html` | Bubble Maker |
| `background-remover.html` | Background Remover |
| `video-layers.html` | Video Layers |
| `outfit-tags.html` | Outfit Tags (built from the Outfit-Idenitfy repository) |
| `manifest.webmanifest` | App name, icons, shortcuts and the Share menu entry for installing |
| `sw.js` | Offline support: keeps the tools and fonts on your device, and receives files shared from other apps |
| `icons/` | App icons |
| `vendor/mediapipe/` | The background remover and face finder (used by Video Layers and Background Remover): Google's MediaPipe vision library (Apache 2.0) with its people, animal and face models. Its usage reporting to Google is switched off in this copy. See the README in that folder. |

Each tool is a single self-contained HTML file with no build step and no server code. Outfit Tags is the only one that talks to an outside service: the AI model you choose, and Danbooru for tag checks. Chat Reel's emoji list comes from [unicode-emoji-json](https://github.com/muan/unicode-emoji-json) and [emoji-data](https://github.com/iamcal/emoji-data), both MIT licensed. The background remover's files are the only ones loaded from elsewhere in the site, and only when you turn it on.

`.github/workflows/fetch-models.yml` downloads newer copies of the background remover's files when run from the Actions tab and puts them on the `cutout-files` branch.

`dev/` holds the helpers for working on the site: `dev/build.py` checks that the pages, offline list and tool switchers agree, bumps the offline version so installed copies update, and packages a test copy for Claude; `dev/test.py` opens every page in a headless browser and reports anything broken. They aren't part of the site itself. `CLAUDE.md` explains the workflow.
