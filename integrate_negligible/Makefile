LATEX = latexmk -pdf -pdflatex="lualatex -halt-on-error -file-line-error -interaction=nonstopmode"
CLEAN = latexmk -C

.DEFAULT_GOAL := intnegligible.pdf

intnegligible.pdf:
	$(LATEX) intnegligible

.PHONY: clean
clean:
	$(CLEAN)
