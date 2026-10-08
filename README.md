# Summer Internship Report – LaTeX Source

**Title:** Learning Digital Design through phone-based Arduino Embedded Systems  
**Student:** Ayaan Syed  
**Institute:** Jamia Millia Islamia, New Delhi  
**Host:** Electrical Engineering Core Labs, IIT Hyderabad  
**Guide:** Prof. G.V.V.  
**Duration:** May 23 – July 15, 2026  

## Contents

| File | Description |
|------|-------------|
| `Internship_Report_Ayaan_Syed.tex` | Main LaTeX source |
| `Internship_Report_Ayaan_Syed.pdf` | Compiled PDF (27 pages) |
| `image1.jpg` … `image8.png` | Figures used in the report |

## How to compile

### Overleaf
1. Create a new project → **Upload Project**
2. Upload this entire folder (or the zip)
3. Set compiler to **pdfLaTeX**
4. Click **Recompile**

### Local (Neovim / terminal)
```bash
pdflatex Internship_Report_Ayaan_Syed.tex
pdflatex Internship_Report_Ayaan_Syed.tex   # second pass for TOC
```

Requires a standard TeX Live / MacTeX installation with packages:  
geometry, fancyhdr, titlesec, booktabs, enumitem, hyperref, graphicx, xcolor, caption, float, parskip, microtype, amsmath, tikz, xurl.
