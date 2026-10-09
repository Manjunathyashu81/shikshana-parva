# ಶಿಕ್ಷಣ ಪರ್ವ · Shikshana Parva

Offline-ready Progressive Web App (PWA) version.

## Files
- `index.html` — main educational web app
- `manifest.webmanifest` — install/app metadata
- `sw.js` — offline cache/service worker
- `icons/icon-192.png` — app icon
- `icons/icon-512.png` — app icon

## GitHub Pages
1. Create a public GitHub repository, for example `shikshana-parva`.
2. Upload the contents of this folder to the repository root.
3. Go to **Settings → Pages**.
4. Select **Deploy from a branch → main → / (root)** and save.
5. Open the published HTTPS URL once while online.
6. On Android Chrome/Edge, use **Install app** or **Add to Home screen**.
7. After the service worker finishes caching, the app can open and work offline.

## Important
The first visit/install must be online. A GitHub Pages URL cannot be reached for the first time with no internet. Once installed and cached, this app is designed to work offline because its main content is contained in `index.html`.
