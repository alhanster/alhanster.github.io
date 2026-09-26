# Alexander Han — personal website

Static site. No build step.

## Files
- `index.html` — the whole site (desktop + mobile, responsive)
- `assets/` — photo, CV, publication figures, polymerase, favicon

## Host on GitHub Pages
1. Create a repo (e.g. `alexhan.github.io` for a root URL, or any name).
2. Upload everything in this folder to the repo root (keep `assets/` as a folder).
3. Repo → Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save.
4. Site goes live at `https://<username>.github.io/` (or `/<repo-name>/`) within a minute or two.

## Updating
- Replace files in `assets/` with the same filenames to swap the photo, CV or figures.
- For content edits, change the design and re-export `index.html`.
