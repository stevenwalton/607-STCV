SRC :=$(wildcard *.tex *.bib)

Survey.pdf: $(SRC)
	pdflatex cvpr
	bibtex cvpr
	pdflatex cvpr

clean:
	rm -f *.glo *.log *.dvi *.gls *.toc *.aux *.ist *.out *.glg *.pdf *.bbl *.blg *.lof *.brf *.nav *.snm

.PHONY: clean
