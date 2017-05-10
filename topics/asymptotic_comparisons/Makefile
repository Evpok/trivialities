LATEX = latexmk -lualatex -halt-on-error -file-line-error -interaction=nonstopmode
CLEAN = latexmk -C

.DEFAULT_GOAL := asymptoticcomparisons.pdf

intnegligible.pdf:
	$(LATEX) asymptoticcomparisons

.PHONY: clean
clean:
	$(CLEAN)
