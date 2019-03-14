My CV
=====

This CV has been generated using [**Awesome CV**](https://github.com/posquit0/Awesome-CV), a LaTeX template for a **CV(Curriculum Vitae)**

## How to Use

#### Requirements

A full TeX distribution is assumed.  [Various distributions for different operating systems (Windows, Mac, \*nix) are available](http://tex.stackexchange.com/q/55437) but TeX Live is recommended.

#### Usage

At a command prompt, run

```bash
$ xelatex cv.tex
```

This should result in the creation of `cv.pdf`

##### List of Publications

You can generate list of publication from [**BibTeX**](http://www.bibtex.org/) source files.
[**BibLaTeX**](https://www.ctan.org/pkg/biblatex) and [**biber**](https://www.ctan.org/pkg/biber) should be available.
To generate document with the list of publications, at a command prompt, run

```bash
$ xelatex cv.tex
$ biber cv
$ xelatex cv.tex
```

