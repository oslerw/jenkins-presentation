# Jenkins Presentation

This presentation was prepared using Pandoc and LaTeX / Beamer. To compile it on
Ubuntu, you will need at least:

- A few of the `texlive` packages, though I'm not sure exactly which. At the
  moment I have the following installed:
    - `texlive-base`
    - `texlive-binaries`
    - `texlive-extra-utils`
    - `texlive-font-utils`
    - `texlive-fonts-recommended`
    - `texlive-generic-extra`
    - `texlive-generic-recommended`
    - `texlive-latex-base`
    - `texlive-latex-extra`
    - `texlive-latex-recommended`
    - `texlive-pictures`
    - `texlive-xetex`
- `pandoc`
- `pandoc-citeproc`
- GNU Make
- The [Fira Sans typeface](https://github.com/mozilla/Fira) by Mozilla

## Compiling

Simply run `make`. For debugging, you can `make debug` to generate the
intermediate LaTeX file that gets turned into the eventual PDF.

## Files

- `arch.markdown` - presentation content
- `template.latex` - the LaTeX template containing document setup and themes
- `references.bib` - bibliographical information for citations

## License

`template.latex` is adapted from the beamer latex template created by John
Macfarlane, and is used and redistributed with changes under the GNU GPL 2.

The logos in the `img/` directory are copyright their respective owners and are
used only to identify referenced products.

All other content is (C) 2016 William Osler and released under a Creative
Commons Attribution 4.0 License (CC BY 4.0)
