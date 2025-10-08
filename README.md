# BEVE POWER — QR Cell Decoder (Online-only Camera)
- Deployed on GitHub Pages.
- Camera scanning works **only when online**. The page loads `html5-qrcode` from CDN if `navigator.onLine` is true.
- When offline, camera UI is disabled; manual QR text entry still works.

## Deploy
Upload all files to your GitHub repository and enable GitHub Pages (Settings → Pages).

## Notes
- Page auto-detects online/offline and toggles camera availability.
- If your network blocks `unpkg.com`, you can switch CDN to jsDelivr in the script (`CDN_LIB` constant).
