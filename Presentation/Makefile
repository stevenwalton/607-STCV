SRC :=$(wildcard *.tex *.bib)

FinalReport.pdf: $(SRC)
	pdflatex Presentation
	bibtex Presentation
	pdflatex Presentation

clean:
	rm -f *.glo *.log *.dvi *.gls *.toc *.aux *.ist *.out *.glg *.pdf *.bbl *.blg *.lof *.brf *.nav *.snm

.PHONY: clean
