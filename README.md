# jorgeiravedra.github.io

Personal academic site. Static HTML, no build step.

## Files
- `index.html` — the whole site (About / Research / CV views, switched by `#about`, `#research`, `#cv`)
- `headshot.jpg` — portrait (400×400)
- `assets/` — create this for research figures (e.g. `assets/nature2026.png`)

## Deploy on GitHub Pages
1. Create a public repo named exactly `jorgeiravedra.github.io`.
2. Add `index.html`, `headshot.jpg` and this README; commit and push to `main`.
3. Repo → Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. The site goes live at https://jorgeiravedra.github.io within a minute or two.

## Editing
- Every unfinished slot is wrapped in `<span class="todo">…</span>` (yellow highlight).
  Search for `todo` to find them all; delete the span tags once filled.
- To add a figure, replace a `<div class="figslot">…</div>` with
  `<img src="assets/your-figure.png" alt="Short description" style="width:100%;margin-bottom:1.4rem">`.
- Colors and fonts are tokens at the top of the `<style>` block (`:root`), with dark-mode values below them.
