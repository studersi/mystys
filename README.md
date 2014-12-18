mystys
======

Description
-----------
Some usefull .sty for working with latex.

Setup
-----
for TeXstudio (& Texmaker) on Linux Mint 17
* git clone git@github.com:studersi/mystys.git
* sudo cp -R ./mystys /usr/share/texmf/tex/latex/
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
* Use \lstinputlisting[label=foo,caption=bar]{pathToFile} for professional captions with profcaption
