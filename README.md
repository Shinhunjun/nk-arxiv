# arXiv Submission Package

This repository contains the LaTeX source files for the paper:

**"How Diplomacy Reshapes Online Discourse: Asymmetric Persistence in Online Framing of North Korea"**

## Contents

- `main.tex` - Main LaTeX file
- `aaai25.sty` - AAAI 2025 style file
- `aaai25.bst` - AAAI 2025 bibliography style
- `references.bib` - Bibliography file
- `sections/` - All section TeX files
  - abstract.tex
  - introduction.tex
  - related_work.tex
  - method.tex
  - data.tex (if used)
  - results.tex
  - discussion.tex
  - conclusion.tex
  - appendix.tex
- `figures/` - All figure PDFs used in the paper
- `tables/` - All table TeX files

## Compilation Instructions

### On Overleaf

1. Create a new project on Overleaf
2. Connect this Git repository to your Overleaf project
3. The main file is `main.tex`
4. Compiler: pdfLaTeX
5. Main document: main.tex

### Local Compilation

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

## arXiv Submission

When submitting to arXiv, upload all files in this directory. arXiv will automatically detect `main.tex` as the main file.

## Notes

- All figures are in PDF format for best quality
- The paper uses AAAI 2025 style (compatible with ICWSM)
- Ethics checklist is included in main.tex
