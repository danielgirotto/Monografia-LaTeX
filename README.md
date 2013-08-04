Monografia-LaTeX (Unochapecó)
=============================

Customização do [abnTeX] (https://code.google.com/p/abntex2/) (ABsurd Norms for TeX) para a Unochapecó. Detalhes
sobre customizações do abnTeX estão disponíveis no [site] (https://code.google.com/p/abntex2/wiki/ComoCustomizar).
Para utilizar este modelo é preciso instalar o pacote abnTeX, as instruções de como instalar esse pacote podem ser
encontradas na página oficial do projeto.

## Como usar?
```
git clone git@github.com:danielgirotto/Monografia-LaTeX.git 
cd Monografia-LaTeX
pdflatex monografia.tex
bibtext monografia
pdflatex monografia.tex ; pdflatex monografia.tex
```

Os comandos "pdflatex" e "bibtex" são apenas uma forma de compilar, recomenda-se fortemente o uso de uma
IDE para o LaTeX:
 - [Kile] (http://kile.sourceforge.net/)
 - [MikTex] (http://miktex.org/)
 - [TeXshop] (http://pages.uoregon.edu/koch/texshop/)
 - [TeXPad] (http://www.textpad.com/)

Licença
=======
      Monografia-LaTeX
      Copyright 2013 Daniel Girotto
      
      This work may be distributed and/or modified under the
      conditions of the LaTeX Project Public License, either version 1.3
      of this license or (at your option) any later version.
      The latest version of this license is in
        http://www.latex-project.org/lppl.txt
      and version 1.3 or later is part of all distributions of LaTeX
      version 2005/12/01 or later.
      
      This work has the LPPL maintenance status `maintained'.
      
      The Current Maintainer of this work is Daniel Girotto.
      
      This work consists of the files monografia.tex and referencias.bib
      and the derived file abnt-unochapeco.sty.
