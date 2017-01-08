# oeadc-doc-latex
An attempt to create LaTeX clone of the OEADC's document [here](http://oeadc.org/Download).
There are also some other documents that are not related to OEADC such as the postpone-
military-service.tex.

## Requirements
- Xelatex have to be used for compilation.
- Some additional packages that are required by the document.

## Building
Run `./script/compile <Tex file>`. The output files will be in `dist/`

## Folder Structre
- `dist/` contains all output files from \LaTeX.
- `extra_document/` is the place to put all other PDF files.
- `images/` is the place to put image files.
- `images/src/` is the palce to put photo editing files.
