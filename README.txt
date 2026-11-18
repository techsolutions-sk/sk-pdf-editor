SK PDF Editor – v1.1
================================
Single-file offline app. New in v1.1: OCR (Tamil + English), Merge PDFs dialog,
drag-to-reorder pages, Extract pages, searchable/copyable Tamil text in saved PDFs.
OCR note: the first OCR run downloads the engine (~15 MB) once; after that it works offline.
 Double-click index.html to run it in Edge/Chrome.

Files
  index.html     – the whole app (all libraries built in, works offline)
  manifest.json  – app details for Microsoft Store (PWA)
  sw.js          – offline cache when hosted online
  icon-*.png     – app icons

Publish to Microsoft Store (same route as Excel Assistant)
  1. Upload all files to a new GitHub repo, enable GitHub Pages.
  2. Open https://www.pwabuilder.com, paste the Pages URL, choose "Windows" package.
  3. In Partner Center reserve the name "SK PDF Editor",
     paste the Package ID / Publisher values into PWABuilder, download the package
     and upload it in a new submission.
