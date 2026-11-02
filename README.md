# Pagewise

A free PDF reader and converter that runs entirely in your browser. Files never leave your device.

Created by **Imran** and **PMGM Studios**.

## Features
- Read PDFs: page navigation, zoom, fit to width, text search
- Make a PDF from pictures (JPG, PNG, WebP, GIF, BMP, SVG), Word (.docx, text only), text files (.txt, .md, .csv, .html), and merge other PDFs
- Convert a PDF to pictures (PNG/JPG, zipped for many pages), plain text, or Word (.docx, text only)

## Put it online with GitHub Pages
1. Create a new repository on GitHub and push these files to the `main` branch.
2. In the repository, open **Settings > Pages** and set **Source** to **GitHub Actions**.
3. The workflow in `.github/workflows/pages.yml` builds and deploys on every push. Your app appears at `https://<your-username>.github.io/<repo-name>/`.

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server` in this folder and visit http://localhost:8000.

## Notes
The app is a single `index.html`. PDF.js, pdf-lib, mammoth and JSZip load from cdnjs, so an internet connection is needed the first time.

© 2026 PMGM Studios. All rights reserved.
