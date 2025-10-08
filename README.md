# BEVE POWER — QR Cell Decoder (GitHub Pages, v2)
**Manual entry always works. Camera works only when online.**
- Prefers native `BarcodeDetector` (no extra files)
- Falls back to CDNs for `html5-qrcode` if needed
- You can safely delete `assets/html5-qrcode.min.js` (not used in this build)

## Deploy
1. Create a public repo (e.g. `beve-qr-decoder`).
2. Upload all files from this ZIP to the repo root.
3. Enable **Settings → Pages → Deploy from a branch → main / root**.
4. Open: `https://<your-username>.github.io/beve-qr-decoder/`

## Notes
- Some older iOS/Safari versions may not support `BarcodeDetector`. The page will auto-try CDNs for `html5-qrcode`.
- If your network blocks both CDNs, scanning won’t be available — manual entry will still work.
