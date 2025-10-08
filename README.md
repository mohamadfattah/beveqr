# BEVE POWER — QR Cell Decoder (GitHub Pages)
Ready to upload to a GitHub repo and deploy with GitHub Pages.

## Features
- Manual QR payload entry (works offline)
- Camera scanning when **online only**
- Library load order: repo-local (`assets/html5-qrcode.min.js`) → unpkg CDN → jsDelivr CDN
- Mobile + desktop responsive design

## Deploy
1. Create a repo (public), e.g. `beve-qr-decoder`.
2. Upload all files from this ZIP to the repo root.
3. Enable **Settings → Pages → Deploy from a branch → main / root**.
4. Open: `https://<your-username>.github.io/beve-qr-decoder/`

## Optional (faster & no-CDN)
Replace the placeholder `assets/html5-qrcode.min.js` with the real library file from:
- https://unpkg.com/html5-qrcode@2.3.7/minified/html5-qrcode.min.js
or
- https://cdn.jsdelivr.net/npm/html5-qrcode@2.3.7/minified/html5-qrcode.min.js
