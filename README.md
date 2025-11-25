# Hawthorn Superheroes: Quick View Guide

If you just want to see the superhero cards with their badges, you can open `index.html` directly or run a tiny local server. Pick whichever feels easiest.

## Option 1: Open the file directly (fastest)
1. Download or clone this folder.
2. Double-click `index.html` to open it in your browser (Chrome, Edge, Firefox, Safari all work).
3. You should see each hero card with colorful badges showing their signature moves.

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
- Each hero card displays small badges listing their **signature moves**.
- Badge colors match the hero’s power type (electric, ice, impact, etc.).

## Troubleshooting
- If images don’t appear when double-clicking `index.html`, use the local server option above.
- Refresh the page (Ctrl/Cmd + R) after starting a server to ensure everything loads.
