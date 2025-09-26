# Planck-Cell Dynamics — Gravity in the Planck-Cell Medium

This archive contains the LaTeX source for the article:

> **Planck-Cell Dynamics — Gravity in the Planck-Cell Medium**  
> Mass as temporal stiffness; gravity as fabric bias.

## Contents

- `main.tex`: article entry point (uses `other_tex/format_macros.tex`).
- `other_tex/`:
  - `format_macros.tex`: shared packages and formatting.
  - optional: `math.tex`, `theorems.tex`, `acknowledgments.tex`, etc.
- `bibliography.bib`: references cited in the paper.
- (Optional) figures and data files if present.

## Build

```
latexmk -pdf -interaction=nonstopmode main.tex
# or
pdflatex -interaction=nonstopmode main.tex
bibtex main
pdflatex -interaction=nonstopmode main.tex
pdflatex -interaction=nonstopmode main.tex
```

If your TeX distribution lacks packages, install common ones (e.g. `hyperref`, `xcolor`, `tcolorbox`, `amsmath`, `amssymb`, `geometry`, `microtype`).

## Notes

- Abstract and body consistently use *Planck-Cell medium*.
- Notation section is a wrapped table to avoid overfull boxes.
- Earth–Moon worked example uses CODATA and NASA values.
- “Other Works” section links to Zenodo DOIs.

## How to Cite

- Langstaff, C. M. (2025). *Temporal Relativity* (Zenodo). DOI: 10.5281/zenodo.17119049  
- Langstaff, C. M. (2025). *Planck-Cell Kinematics* (Zenodo). DOI: 10.5281/zenodo.17168478  
- Langstaff, C. M. (2025). *Planck-Cell Mass* (Zenodo). DOI: 10.5281/zenodo.17209646

## License

Unless otherwise stated (e.g., a `LICENSE` file), the LaTeX is released under a permissive license by the author.

---
Generated README on 2025-09-26.
