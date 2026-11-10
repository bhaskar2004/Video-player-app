# Lumen for Android

Your Lumen HTML player wrapped in a native WebView (bundled offline in `app/src/main/assets/index.html`).

## Get the APK
**Android Studio:** File → Open → this folder → Run ▶ (or Build → Build APK).
**GitHub (no Android Studio):** push this folder to a repo → Actions → "Build APK" → download `Lumen-debug-apk`.

## What the wrapper adds
- Native file picker for videos and subtitles
- Fullscreen via native view, landscape/portrait lock driven by the page
- Edge-to-edge immersive mode, notch support
- Screen stays on while a video is fullscreen
- Back button closes the player first, then exits
- Picture-in-picture when you swipe home from fullscreen
- Pauses when the app is sent to the background (unless in PiP)
- Pasted http:// and https:// video links work
