# A template for the final year BSc project

Files are in one of two directories `tex` (for the tex files) and `img` (for
image files) directory which contains:

    tex
    ├── acknowledgements.tex
    ├── bibliography.bib
    ├── frontcover.tex
    ├── main.tex
    ├── chapters
    │   └── chapter1.tex
    │   └── chapter2.tex
    │   └── chapter3.tex
    img
    ├── plot1.pdf
    ├── plot2.pdf
    ├── markov_chain.tex
    ├── universitylogo.eps

Compiling the `main.tex` file pulls in all the other files as required.  The
`chapter{1,2,3}.tex` files would be where the main part of your content goes.

In the `img` directory there are a combination of `pdf` and `eps` images as
well as a a tikz diagram (`markov_chain.tex`).

To handle all these files I recommend compiling with `xelatex`.
