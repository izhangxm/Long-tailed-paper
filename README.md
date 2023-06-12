# Paper source code in Latex.

## Requirments
- vscode with Latexshop extention
- texlive2022 or later
- texlive bin in your path

## How to use
build and view.

## Trouble shot
### 1. missing `*.sty` file
use `tlmgr` command to search which package contains the file. example:
```bash
$ tlmgr search --global --file "/perpage.sty" 
tlmgr: package repository https://mirrors.tuna.tsinghua.edu.cn/CTAN/systems/texlive/tlnet (not verified: gpg unavailable)
bigfoot:
        texmf-dist/tex/latex/bigfoot/perpage.sty
```
the results show that it is contained in `bigfoot` package.
```
tlmgr install bigfoot
```

### 2. other errors
please search solution in the Internet or create a new issue.