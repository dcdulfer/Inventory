# Barraco's Daily Purchasing PWA

A self-contained, offline-capable Progressive Web App (PWA) built for restaurant managers to walk stocking locations, record daily reorder quantities, drag-and-drop items into shelf order, and copy plain-text supplier orders straight into SMS messages.

## Files Included in This Repository
- `index.html` — Complete application UI, state engine, drag-and-drop shelf ordering, SMS clipboard copy, and CSV import/export.
- `manifest.json` — Web App Manifest enabling native home-screen installation on Android, iPhone, and iPad.
- `sw.js` — Service Worker caching app shell assets for offline walk-in cooler reliability.
- `icon-192.png` & `icon-512.png` — Android / Chrome PWA home screen and splash icons.
- `apple-touch-icon.png` — iOS / iPadOS home screen icon.
- `sample-barracos-stock.csv` — Starter 60-item CSV template (`Item Name, Stocking Location, Supplier, Unit`).

## Deploying to GitHub Pages
1. Create a new GitHub repository (e.g., `barracos-purchasing`).
2. Upload all files from this folder directly into the root of the repository (so `index.html`, `manifest.json`, `sw.js`, and the `.png` icons sit at the top level).
3. In your GitHub repository, open **Settings → Pages**.
4. Under **Build and deployment → Source**, select **Deploy from a branch**, choose `main` and `/ (root)`, and click **Save**.
5. Wait ~60 seconds for GitHub Pages to publish your HTTPS URL (`https://<your-username>.github.io/<repo-name>/`).

## Installing on Your Devices
- **Android (Chrome):** Open your GitHub Pages URL in Chrome, tap the **⋮** menu, and select **Install app** (or **Add to Home screen**).
- **iPhone / Foldable iPhone / iPad (Safari):** Open your GitHub Pages URL in Safari, tap the **Share** button, and select **Add to Home Screen**.
