# Report-Template

A simple LaTeX template for CS courses in Zhejiang University

## Install on macOS

* package `minted` requires `python`, `pygments` and its dependencies.

  Add `minted.sty` to the directory of your TeX distribution, generally `/usr/local/texlive/YOUR-VERSION/texmf-dist/tex/latex/base`, then run
  
  ```bash
  $ sudo texhash
  ```
  
  To install `pygments`,run
  
  ```bash
  $ sudo easy_install pip && pip3 install pygments
  ```
  
  You can run 

  ```bash
  $ pygmentize
  ```

  to check if it functions well.

## Usage

* compile with XeLaTeX(简体中文) or pdfLaTeX(English)
* add `-shell-escape` to compile options so that shell commands can be called while compiling
* add `-8bit` to compile options so that `TAB` can be displayed correctly in `minted` environment

## License

[MIT License](LICENSE) © Zhiyuan Pan
