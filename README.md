# Personal Website

This is a static academic website for GitHub Pages, generated from jemdoc source files.

## Edit

- Edit homepage content in `index.jemdoc`.
- Edit publication content in `publications.jemdoc`.
- Edit activity content in `activaties.jemdoc`.
- Edit visual styling in `jemdoc.css`.
- Replace the portrait at `pics/headshot_recent.jpg` if needed.

## Build

Regenerate HTML after editing a `.jemdoc` file:

```bash
python3 jemdoc.py index.jemdoc
python3 jemdoc.py publications.jemdoc
python3 jemdoc.py activaties.jemdoc
```

## Deploy

Push the generated `.html` files, `jemdoc.css`, image files, and source `.jemdoc` files to a GitHub repository named `username.github.io`. GitHub Pages will serve `index.html` as the homepage.
