# About

This is the official documentation for QuimP software.

# How to use it

This repository contains `LaTeX` source of the QuimP documentation. Compiled *pdf* file related to currently released version of QuimP is available at [QuimP homepage](http://www2.warwick.ac.uk/fac/sci/systemsbiology/staff/bretschneider/quimp/).
This repository is included in [QuimP](https://github.com/CellDynamics/QuimP) as submodule. 

## Building

One needs to have full LaTeX distribution installed on the system. Then, to build the documentation type:
```sh
cd Docs
pdflatex QuimP_Guide.tex
bibtex QuimP_Guide.aux
pdflatex QuimP_Guide.tex
pdflatex QuimP_Guide.tex
```

The final document is in `Docs/QuimP_Guide.pdf`.

# Links
- QuimP homepage: <http://www2.warwick.ac.uk/fac/sci/systemsbiology/staff/bretschneider/quimp/>
- QuimP GitHub page (contains Wiki and bug tracker): <https://github.com/CellDynamics/QuimP>