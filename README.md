# LaTeX CV

Source code for my CV, written in LaTeX.

The visual design is inspired by the aesthetic of [Warp Records](https://warp.net/) — bold flat colors, grotesque typography, and the sleeve/catalogue look of their releases — reinterpreted into a clean, professional CV layout.

The CV is kept intentionally compact since I use it mainly as a practical document for applications.

## Files

- `cv.tex` — LaTeX source of the CV.
- `cv.pdf` — Compiled version.

## Compiling

This document requires **XeLaTeX** (not pdfLaTeX), since it loads system fonts via `fontspec`:

- [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk)
- [IBM Plex Sans](https://fonts.google.com/specimen/IBM+Plex+Sans) / [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono)

Install these fonts locally, then compile with:

```bash
xelatex cv.tex
```

> Note: Overleaf's default compiler is pdfLaTeX. If using Overleaf, change the compiler to **XeLaTeX** in the project settings (Menu → Compiler), and make sure the fonts above are available (either installed on Overleaf's TeX Live distribution or uploaded to the project).
