MY FAMILY VAULT — FULL FUNCTIONALITY

Files to replace in GitHub root:
index.html
sw.js
manifest.json
icon-192.png
icon-512.png

Features:
- Local IndexedDB storage only for family records, documents, attachments, health values
- Family profiles
- Categories: Health, Education, Warranty, Jewellery, Insurance, Certificates, Vehicle, Property, Other
- View, edit, replace, share/export, delete documents
- Health text-PDF extraction using pdf.js in the browser
- Review extracted health values before saving
- Health overview, trends, reports, comparison
- Search
- Reminders using expiry/renewal dates
- Backup/restore including attachments
- Offline PWA shell

Privacy:
No personal records are intentionally sent to GitHub or a backend. The app code is hosted by GitHub Pages; data is stored in Safari IndexedDB. pdf.js is loaded as a library from cdnjs and cached. PDF bytes are processed in the browser, not uploaded to cdnjs.

After uploading:
1. Wait for GitHub Pages to deploy.
2. Open https://skpbhel.github.io/my-family-vault/ in Safari.
3. Pull to refresh.
4. If old UI persists, remove/re-add the Home Screen app or clear site cache only after taking a backup.
