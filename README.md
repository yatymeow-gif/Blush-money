# Blush Money

A private, offline-first personal finance planner (Singapore, SGD). Single-page web app — no server, no accounts, no tracking, no paid services.

- **Open the app:** `index.html`
- **User guide:** `GUIDE.html`
- **Your data** is stored only in your own browser (IndexedDB). It is never uploaded to this website or repository.

## Hosting on GitHub Pages
1. Upload every file in this folder to the root of a public repository (keep `.nojekyll`).
2. Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.
3. Open `https://<username>.github.io/<repository>/` in Safari (iPhone) or Chrome (Android) and choose **Add to Home Screen** / **Install app**.

## Updating
Back up first (Settings → Back up). Replace `index.html`, then change `CACHE` in `sw.js` (e.g. `blush-money-v1.0.1`) so installed copies refresh. Your data is kept because it lives in the browser, not in these files.

## Source
`source/` holds the readable code. Run `python3 source/build.py` to rebuild `index.html` from it.
