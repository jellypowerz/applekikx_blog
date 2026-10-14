# jelli pops page

A static personal page. No build step, no framework — just `index.html` and `style.css`.

## Quickstart

1. Clone or open this folder.
2. Open `index.html` in a browser:
   - Finder: double-click `index.html`
   - Terminal:

     ```bash
     open index.html
     ```

3. Edit `style.css` (page styles) or `index.html` (markup), then refresh the browser.

## Optional: local server

Some browsers treat `file://` pages differently (for example with images or later fetch calls). If something looks off, serve the folder:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).
