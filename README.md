# URF–Astro: A Density–Redshift Screened Scalar Field Solution to the Cusp–Core Problem

**Constraints from SPARC, JWST, and DESI DR2 with NEES (AI Co-Author)**

URF–Astro is a screened ultralight scalar field framework that reproduces kpc-scale cores in dwarf galaxies while remaining consistent with cosmological bounds. This repo hosts the LaTeX sources, supplements, and plotting scripts for the figures.

## What’s here
- `docs/manuscript/urf_astro_main.tex` – main paper (journal-style)
- `docs/supplements/` – Concept & Explanation, Methods & Calculations, FAQ, NEES AI Peer Review
- `docs/ethics/` – AI Co-Author Declaration + Zenodo ethics note
- `src/plots/` – scripts to regenerate key figures
- `figures/` – exported PNGs ready for Overleaf/journal
- `env/` – reproducible Python environment

## Reproducibility
```bash
conda env create -f env/environment.yml
conda activate urf-astro
python src/plots/make_meff_rho.py
python src/plots/make_transfer.py
python src/plots/make_forecasts_panel.py
