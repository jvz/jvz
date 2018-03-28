# Matt Sicker's CV

This repository hosts my CV/resume which is written in LaTeX.

## Building

On macOS, just install [MacTeX][mac]. On Ubuntu, the following minimal install works:

    apt install --no-install-recommends texlive latex-xcolor texlive-latex-extra texlive-fonts-extra

Then run `pdflatex` on the file a couple times:

    pdflatex cv.tex
    pdflatex cv.tex

[mac]: https://www.tug.org/mactex/mactex-download.html
