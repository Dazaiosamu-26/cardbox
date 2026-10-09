# Cardbox

Flashcards with spaced repetition. Study by revealing the answer, picking from multiple choice, or typing it.

Runs entirely in the browser. Cards and progress are saved on the device you use, so use Export > Backup (JSON) to move them to another device.

## Publish with GitHub Pages
1. Create a new public repository (for example `cardbox`).
2. Upload everything in this folder to the repository root (`index.html`, `manifest.webmanifest`, `sw.js`, `icons/`).
3. Open Settings > Pages. Under Build and deployment choose Deploy from a branch, branch `main`, folder `/ (root)`, then Save.
4. After a minute the app is live at `https://<your-username>.github.io/cardbox/`.

## Install it as an app
- Android (Chrome): menu > Install app.
- iPhone (Safari): Share > Add to Home Screen.
- Desktop (Chrome or Edge): the install icon in the address bar.

## Updating
Change a file, commit it, and raise `VERSION` in `sw.js` so installed copies refresh.
