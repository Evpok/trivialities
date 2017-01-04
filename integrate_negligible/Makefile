LATEX = latexmk -pdf -pdflatex="lualatex -interaction=nonstopmode"
CLEAN = latexmk -C

.DEFAULT_GOAL := intnegligible.pdf

intnegligible.pdf:
	$(LATEX) intnegligible

.PHONY: clean
clean:
	$(CLEAN)
