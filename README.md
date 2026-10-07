# Bundi Runner — Deployable Web Version

This is a static web game. No backend, database, Node.js, or build step is required.

## Files
- `index.html` — complete game
- `manifest.webmanifest` — installable/PWA metadata
- `README.md` — deployment instructions

## Run locally
Open `index.html` in a modern browser.

## Deploy
Upload the entire folder to any static hosting provider. The entry file is `index.html`.

### GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html` and `manifest.webmanifest`.
3. In Settings → Pages, choose the main branch/root folder.
4. Open the generated Pages URL.

### Netlify / Cloudflare Pages / Vercel
Upload/import the folder as a static site. No build command and no publish directory are required; the root folder contains `index.html`.

## Controls
- Mobile: tap to jump.
- Desktop: Space or Up Arrow to jump.
- P / Escape: pause.

## Notes
The game stores the best score in browser localStorage. The game itself has no external image, font, JavaScript, or API dependencies, so gameplay is self-contained and can work without internet after the page has been loaded.
