# PDFTK
Minimal docker image containing [pdftk](https://www.pdflabs.com/docs/pdftk-man-page/) for manipulating PDFs.

Usage is the same as PDFTK. For example to merge two PDFs, run:

`docker run --rm -it -v /path/to/local/directory:/data bwindsor/pdftk file1.pdf file2.pdf file3.pdf cat output combined.pdf`
