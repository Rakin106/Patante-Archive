# PatentePlay — GitHub Pages

A simple static study dashboard for the Italian driving licence.

## Publish with GitHub Pages

1. Create a new GitHub repository (for example `patenteplay`).
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then Save.
6. Wait for the Pages deployment. Your site URL will look like:
   `https://YOUR-USERNAME.github.io/patenteplay/`

No build tools, Node.js, or GitHub Actions workflow are required.

## Features

- 25 study chapters and the YouTube video links extracted from the supplied chat export.
- Per-video completion tracking, search, and chapter filters.
- Personal notes saved in the browser.
- JSON export/import for moving progress between devices.
- Catalogue of PDF filenames mentioned in the chat.

## Important

The chat export listed PDF filenames but did not include the actual PDF documents. To make PDFs available on the site, add them to the repository (for example in a `pdfs/` folder) and then add links to them in `index.html`.

Progress and notes are stored in the browser's local storage. They do not automatically sync between devices. Use **Esporta backup** and **Importa backup** to transfer them.
