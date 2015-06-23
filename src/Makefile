
all:
	xelatex -interaction=nonstopmode ./dissertation.tex && bibtex diploma 

with_index:
	xelatex -interaction=nonstopmode ./dissertation.tex && bibtex diploma && xelatex -interaction=nonstopmode ./diploma.tex
