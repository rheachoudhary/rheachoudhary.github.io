# rheachoudhary.github.io

My personal academic website, served at <https://rheachoudhary.github.io>.

It's a single static page — no build step. To make changes, edit `index.html`
and push to the `main` branch; GitHub Pages redeploys automatically in ~1 minute.

## Editing cheatsheet

- **Name / title / affiliation** — top of `index.html`, in the `<header>` block.
- **Links row** (Email, CV, GitHub, Scholar, LinkedIn) — the `<nav class="links">` block.
- **About / Research / Papers / Contact** — the `<section>` blocks, in order.
- **Headshot** — drop a square image named `photo.jpg` in this folder (or delete the `<img class="photo">` line).
- **CV** — drop a file named `cv.pdf` in this folder.
- **Colors** — the `:root` CSS variables near the top (light and dark mode).
