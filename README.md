# BEVE POWER — QR Cell Decoder

This is a lightweight, responsive web app for decoding GREAT POWER cell QR payloads used in BEVE POWER TITAN batteries.

## How to deploy
1. Upload the contents of this folder to any static host (Netlify, GitHub Pages, Vercel static, Nginx/Apache).
2. Open `index.html`.

## Camera scanning
- The app loads `html5-qrcode` from a public CDN at runtime to keep the package small.
- If you need **offline** scanning, download the library file to `./assets/html5-qrcode.min.js` and change `LIB_URL` at the bottom of `index.html` to point to the local file.

## Logo
- The page references your logo hosted at:
  https://i.postimg.cc/v8CLk3Nv/Screenshot-2025-09-28-104524.png
- To ship the logo locally, place it in `assets/logo.png` and update the `<img>` `src` in `index.html`.

## Notes
- Decoding rules for Year/Month/Day follow your provided QR definition.
- Improve the parsing by providing more sample codes if formats vary.
