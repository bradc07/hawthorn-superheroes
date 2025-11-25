# Hawthorn Superheroes: Quick View Guide

If you just want to see the superhero cards and open their dossiers, you can open `index.html` directly or run a tiny local server. Pick whichever feels easiest.

## Option 1: Open the file directly (fastest)
1. Download or clone this folder.
2. Double-click `index.html` to open it in your browser (Chrome, Edge, Firefox, Safari all work).
3. You should see each hero card—click any card to open its dossier and signature moves.

## Option 2: Run a local web server (helpful if images don’t load)
This keeps paths tidy and works on any platform.

### Using Python (already installed on most systems)
```bash
# From inside the project folder
python -m http.server 8000
```
Then visit <http://localhost:8000> in your browser.

### Using Node.js (if you prefer npm)
```bash
npm install -g serve
serve . -l 8000
```
Then visit <http://localhost:8000> in your browser.

## What to look for
- Each hero card shows three illustrated badges along the bottom of the portrait—each badge is an icon for one of their signature moves.
- Click a hero card to open the dossier modal with their **signature moves** and power ratings.

## Troubleshooting
- If images don’t appear when double-clicking `index.html`, use the local server option above.
- Refresh the page (Ctrl/Cmd + R) after starting a server to ensure everything loads.

## Need the whole `index.html` file?
- The complete file already lives in this folder as `index.html`—no patches needed.
- To grab a copy without any extra tools, just download or copy that file from the folder you received.
- If you want to download only `index.html` from a browser (for example from GitHub):
  1. Open the repository page.
  2. Click `index.html` in the file list.
  3. Press the **Raw** button so the full file opens in your browser.
  4. Use **File → Save Page As...** (or right-click → **Save As...**) to save it locally as `index.html`.
- If you have Git available, you can export everything (including `index.html`) into a zip by running:
  ```bash
  git archive --format=zip -o hawthorn-superheroes.zip HEAD
  ```
  The zip will contain the full `index.html` for you to open.
