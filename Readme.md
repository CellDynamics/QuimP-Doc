# About

This is the official documentation for QuimP software.

# How to use it

This repository contains `LaTeX` source of the QuimP documentation. Compiled *pdf* file related to currently released version of QuimP is available at [QuimP homepage](warwick.ac.uk/quimp). The **develop** follows development version of QuimP, whereas **master** contains documentation for already released QuimP.

Both branches are compiled to Html/PDF manual by script that runs daily arond 6am and uploaded to:

1. <http://pilip.lnx.warwick.ac.uk/docs/develop/QuimP_Guide.html> - develop branch
2. <http://pilip.lnx.warwick.ac.uk/docs/master/QuimP_Guide.html> - master branch

## Building

One needs to have full LaTeX distribution installed on the system. Then, to build the documentation type:
```sh
cd Docs
pdflatex QuimP_Guide.tex
pdflatex QuimP_Guide.tex
bibtex QuimP_Guide.aux
pdflatex QuimP_Guide.tex
pdflatex QuimP_Guide.tex
```

The final document is in `Docs/QuimP_Guide.pdf`.

# Links
- QuimP homepage: <http://warwick.ac.uk/quimp>
- QuimP GitHub page (contains Wiki and bug tracker): <https://github.com/CellDynamics/QuimP>
- Html version of manual: <http://pilip.lnx.warwick.ac.uk/docs/develop/QuimP_Guide.html>
