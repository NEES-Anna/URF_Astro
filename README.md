# URF–Astro V2 (Overleaf / arXiv)

**Date:** 2025-10-05

## Compile locally
```
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

## Folder layout
- `main.tex` — paper
- `refs.bib` — references
- `figures/` — placeholder PDFs; replace with real plots
- `LICENSE` — MIT

## arXiv upload
- Upload the **ZIP** as source.
- Ensure `main.tex` is the root file.
- Category: **astro-ph.CO**.
- Add keywords: dark matter; scalar field; cusp-core; DESI; JWST.

## GitHub
```
git init
git add .
git commit -m "URF-Astro V2 initial"
git branch -M main
git remote add origin <YOUR-REPO-URL>
git push -u origin main
```