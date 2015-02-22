mystys
======

Description
-----------
Some usefull .sty for working with latex.

Setup
-----
for TeXstudio (& Texmaker) on Linux Mint 17
* git clone git@github.com:studersi/mystys.git
* sudo cp -r ./mystys/ /usr/share/texlive/texmf-dist/tex/latex/
* sudo texhash

import like other packages in .tex file

Packages
--------
* profcaption
* simushdr
* simuslistings
* tikz-er2

Styles in simuslistings
-----------------------
* simusTerminalCommand
* simusSQL
* simusCypher

Hints
-----
* Use \lstset{style=<STYLE>} at the top to set default for the document
* For professional captions with profcaption, add option [caption=foobar] to listing
