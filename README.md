# Depth Chart

An interactive depth chart for a rugby squad. Assign players to positions, see who covers each shirt number, and review the full 15 at a glance. It's a single static page with no build step and no dependencies.

## Run it

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Deployment

Pushes to `main` publish the site through GitHub Pages (`.github/workflows/jekyll-gh-pages.yml`).

## Notes

- Plain HTML, CSS and JavaScript in one file; the only external resource is a Google Font.
- Layout is designed for tablet and desktop widths.
