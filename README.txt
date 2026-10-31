DEUTSCH GRAMMATIK ARCADE — iPhone / GitHub Pages package

Files in this folder:
- index.html: the game
- manifest.webmanifest: Home Screen / PWA metadata
- service-worker.js: offline cache
- icon-192.png, icon-512.png, apple-touch-icon.png: app icons

Publish with GitHub Pages:
1. Create a new PUBLIC GitHub repository (for example: deutsch-grammatik).
2. Upload ALL files from this folder into the repository root.
3. GitHub repository → Settings → Pages.
4. Under Build and deployment choose “Deploy from a branch”.
5. Select branch “main”, folder “/ (root)”, then Save.
6. Open the GitHub Pages address in Safari on the iPhone.
7. Safari → Share → Add to Home Screen → Add.
8. Launch from the Home Screen once while online. After that, the service worker allows offline use.

Notes:
- Scores and streaks are stored locally on each device/browser.
- If you clear Safari website data, those saved scores can be removed.
- Sound uses the browser audio engine and may require the first tap before iOS allows audio.
