# Manual of NDELOC v1.2.17
This is the current manual of the NDELOC v.1.2.17 program to compute multicenter localization and delocalization indices via the real space partitionings, such as QTAIM, Hirshfeld-based and ELF schemes.

## Author and collaborators
  - Nicolás Otero Martínez - nom05 (at) uvigo.es - University of Vigo

## Software employed to obtain examples
[Chemcraft](https://chemcraftprog.com/)
After that, I edited the files with [GIMP](https://www.gimp.org/).

## MIT license
See corresponding file called [`LICENSE`](LICENSE) for more details.

## Compile the code
After cloning the repository, enter in the new directory, go to `figures` and compile the simplified flowchart (it is a figure necessary in the main LaTeX code of the manual:
```
pdflatex flowchart.tex
```
After the successful compilation go back to the main directory and compile the code:
```
pdflatex manual-ndeloc-220413-memoir.tex
pdflatex manual-ndeloc-220413-memoir.tex
biber manual-ndeloc-220413-memoir
pdflatex manual-ndeloc-220413-memoir.tex
pdflatex manual-ndeloc-220413-memoir.tex
```
