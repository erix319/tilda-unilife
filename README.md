# UniHilfe

Study-in-Austria consultancy — a Tilda landing page.

**Live:** https://erix319.github.io/tilda-unilife/

## About

Lead-generation page for a consultancy helping students apply to Austrian universities — application walkthrough, support scope from picking a university through to finding housing, pricing position against competitors, and a free-consultation booking form.

Interface language is Russian.

## Stack

- **Tilda** — Zero Block layout, built from the platform's page builder
- **Static site** — plain HTML, CSS and JavaScript, no build step and no server
- Tilda's runtime bundle: grid, lazy-loading, forms, menu and animation modules

## Running locally

Any static file server works. From the repository root:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>.

Opening `index.html` straight off the filesystem mostly works too, but a
server is closer to how it is actually deployed.

## Layout

```
index.html   the page itself
assets/      41 files — styles, scripts, images and fonts
```
