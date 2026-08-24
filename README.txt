MY FAMILY VAULT v1

Approved UI + local-first architecture.

INSTALL / UPDATE ON GITHUB PAGES
1. Upload/replace index.html, sw.js, manifest.json, icon-192.png, icon-512.png
   in the root of skpbhel/my-family-vault.
2. Wait for GitHub Pages to redeploy.
3. Open https://skpbhel.github.io/my-family-vault/ in Safari.
4. Pull to refresh. If the Home Screen app still shows an older UI, reopen the
   Safari site first, then launch the Home Screen app again.

PRIVACY
- No family/health/document data is uploaded to GitHub.
- Records and attachments are stored in IndexedDB in Safari on the device.
- PDF extraction happens in the browser.
- pdf.js is loaded/cached as an app library; no health PDF is uploaded to it.
- Export backups regularly to a private location.

TEXT PDF HEALTH FLOW
Add Report -> local PDF text read -> extracted values shown for review ->
Confirm & Save -> Overview / Trends / Reports / Compare.

SCANNED PDFs
The original file is still saved, but automatic OCR is not included in v1.
