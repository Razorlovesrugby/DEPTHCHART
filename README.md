# Depth Chart

A drag-and-drop depth chart for a rugby squad, built for the Belize Rugby 2025-26 performance squad. Players are listed position by position and automatically tiered as starter, backup or development depending on where they sit in each list.

## Features

- Drag players to reorder depth within a position
- Drag sidebar rows to reorganise positions
- Move a player to another position from a modal
- Tier labels (starter, backup, development) derived from list order and position

## Run it

A single static page with no build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Deployment

Pushes to `main` publish the site through GitHub Pages (`.github/workflows/jekyll-gh-pages.yml`).

## Notes

- Plain HTML, CSS and JavaScript in one file. The only external resource is a Google Font.
- Changes are held in memory only and reset on reload.
