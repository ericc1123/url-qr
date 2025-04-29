# URL & QR Expander

Single-page tool that:

* **Un-shortens** links (Bitly, t.co, etc.)
* **Decodes** QR codes in uploaded **images or PDFs**
* Stores the **file name** and the **original shortened URL**
* Splits **UTM** parameters
* Exports everything to **CSV**

## Quick start

1. Drop `index.html` (this repo) into any web folder.
2. Open the file in a modern browser.

## GitHub Pages

* Put `index.html` in the repo root.
* Settings → Pages → Branch `main` / **root**.
* Live at  
  `https://<username>.github.io/<repo>/`

## Tech

* **jsQR** — client-side QR decoding  
* **pdf.js** — renders PDFs so jsQR can scan each page  
* **Unshorten.me API** — follows redirects (avoids CORS)  
* No build step, no backend.
