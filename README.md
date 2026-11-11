# Diglot

Read a PDF side by side: the original text on the left, its translation on the right.

Open a PDF, pick the original and target languages, and Diglot translates it page by page. Translation runs on your device with Chrome's built-in Translator API, so the file is never uploaded.

## Usage

Serve the folder and open it in desktop Chrome 138 or newer, e.g. `python3 -m http.server` and visit `http://localhost:8000`. (Opening `index.html` directly also works in Chrome, but Safari blocks the bundled fonts on `file://` pages.)
