LATEX = latexmk -lualatex -halt-on-error -file-line-error -interaction=nonstopmode
CLEAN = latexmk -C

.DEFAULT_GOAL := weierstrass.pdf

intnegligible.pdf:
	$(LATEX) weierstrass

.PHONY: clean
clean:
	$(CLEAN)
