# Quarto template for AGH BEng/MSc theses

To start a new blank project, execute `quarto use template habemus-python/quarto-agh-thesis`.

To render it to a pdf, do: `quarto render thesis.ipynb`.

Note that to make it work, `quarto` needs to be executed in an environment in which the following tools work OK:
- [Jupyter](https://jupyter.org/) (on Debian/Ubuntu: `apt-get install jupyter`)
- [LuaTeX](https://en.wikipedia.org/wiki/LuaTeX) (on Debian/Ubuntu: `apt-get install texlive-luatex`)
- [rsvg-convert](https://en.wikipedia.org/wiki/Librsvg) (on Debian/Ubuntu: `apt-get install librsvg2-bin`)
- [Biber](https://en.wikipedia.org/wiki/Biber_(LaTeX)) (on Debian/Ubuntu: `apt-get install biber`)
- [Biblatex](https://biblatex.org/) (on Debian/Ubuntu: `apt-get install texlive-bibtex-extra`)  

See [Quarto docs](https://quarto.org/docs/extensions/starter-templates.html#using-a-template) 
  to learn more about using templates.

Template based on [Overleaf template](https://www.overleaf.com/latex/templates/praca-dyplomowa/kbwcrcmczypy) 
  by [Krzysztof Malarz](https://home.agh.edu.pl/~malarz/).
