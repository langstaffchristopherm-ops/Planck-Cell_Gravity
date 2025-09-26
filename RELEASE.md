# Release Notes — Planck-Cell Gravity

## v0.1.0 (2025-09-26)

**Added**
- Initial public drop of LaTeX sources for *Planck-Cell Dynamics — Gravity in the Planck-Cell Medium*.
- Notation table with wrapped column to avoid overfull boxes.
- Earth–Moon worked example using CODATA/NASA parameters.
- “Other Works by the Author” section with Zenodo DOIs.

**Changed**
- Abstract updated to use Planck-Cell terminology and split into paragraphs.
- Replaced “entropy medium” with “Planck-Cell medium” throughout.
- Clarified identifiability: only the product \(\beta C\) is fixed in the Newtonian limit.

**Fixed**
- Overfull \hbox warnings from the notation list (now a table) and Earth–Moon parameters line (split across displays).

**Notes**
- Bibliography includes standard references (Newton, Einstein, Will, Eddington) and factual sources (CODATA, NASA fact sheets, MICROSCOPE bound).
- Build with `latexmk -pdf` or `pdflatex`/`bibtex` sequence.
