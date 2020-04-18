# Report-Template
A simple LaTeX template for CS courses in Zhejiang University

## Instructions
* compiled with XeLaTeX
* package `minted` requires `python`, `pygments` and its dependencies.

  Add `minted.sty` to the directory of your TeX distribution, generally `/usr/local/texlive/YOUR-VERSION/texmf-dist/tex/latex/base`, then run `sudo texhash`.
  
  To install `pygments`,run `sudo easy_install pip && pip3 install pygments`
* add `--shell-escape` to compile options so that shell commands can be called while compiling
* add `-8bit` to compile options so that `TAB` can be displayed correctly in `minted` environment
