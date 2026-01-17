# Research Communication Portfolio (GitHub Pages)

This is a lightweight, single-page portfolio site (HTML/CSS/JS) showcasing:
- Policy briefs
- Research summaries (researcher-spotlight style)
- Social and internal comms examples

## Structure
- `index.html` – the site
- `template.css` / `template.js` – styling and interactions
- `assets/hero.svg` – hero illustration
- `assets/papers/` – source PDFs linked from the site

## Publish on GitHub Pages
1. Create a repo (e.g., `research-policy-writing`).
2. Add the files above at the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set:
   - Source: **Deploy from a branch**
   - Branch: `main` (or `master`) / `/root`
5. Save.

## Notes
- The PDFs are large. If GitHub warns about file size, use **Git LFS** or host the PDFs elsewhere and replace the links in `index.html`.
