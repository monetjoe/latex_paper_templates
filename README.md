# ICASSP Latex Template
Customized [ICASSP Latex template](https://signalprocessingsociety.org/event-names/icassp) for VSCode

[![license](https://img.shields.io/github/license/monetjoe/latex_templates.svg)](./LICENSE)

The following style files and templates are available for users of LaTeX and Microsoft Word:

* LaTeX style file with margin, page layout, font, etc. definitions.

* BiBTeX style file with bibliography style definitions.

* LaTeX template file, an example of using the `spconf.sty` and `IEEEbib.bst` files above. 

* Sample `*.bib` and `refs.bib` files.

* Sample `image1.eps`, `image3.eps` and `image4.eps` files, referenced in the LaTeX template.

We recommend that you use the Word file or LaTeX files to produce your document, since they have been set up to meet the formatting guidelines listed above. When using these files, double-check the paper size in your page setup to make sure you are using the letter-size paper layout (8.5" X 11") or A4 paper layout (210mm X 297mm). The LaTeX environment files specify suitable margins, page layout, text, and a bibliography style.

In particular, with LaTeX, there are cases where the top-margin of the resulting Postscript or PDF file does not meet the specified parameters. In this case, you may need to add a \topmargin=0mm command just after the \begin{document} command in your .tex file. The spacing of the top margin is not critical, as the page contents will be adjusted on the proceedings. The critical dimensions are the actual width and height of the page content.

## Code download
```bash
git clone -b icassp git@github.com:monetjoe/latex_templates.git
cd latex_templates
```

