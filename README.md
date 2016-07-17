# Master's Thesis

## Welcome to my thesis!
In order to compile my LaTeX document, you are going to need latex with
many of the texlive packages. The following list demonstrates how to compile the
document:

- `pdflatex -shell-escape doc/eilar_thesis_2016.tex`
- `bibtex *.aux`
- `pdflatex -shell-escape doc/eilar_thesis_2016.tex`
- `pdflatex -shell-escape doc/eilar_thesis_2016.tex`

You have to compile the document multiple times to get the references to show up
correctly. 
