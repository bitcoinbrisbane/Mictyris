# Mictyris

Landing page for **Mictyris.com**, a holding company backing a marine delivery project.

Named after *Mictyris*, the soldier crab that marches the shoreline in coordinated ranks.

## Contents

- `index.html`: single-page site, fully self-contained (inline CSS + inline SVG crab logo, no build step, no dependencies).

## Preview

Open `index.html` in any browser, or serve locally:

```sh
python3 -m http.server
# then visit http://localhost:8000
```

## Deploy

Because it's a single static file, it deploys anywhere: GitHub Pages, Netlify, Cloudflare Pages, S3, etc. Point the `mictyris.com` domain at the host and you're live.
