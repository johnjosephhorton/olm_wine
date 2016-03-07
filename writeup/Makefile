olm_wine.pdf: olm_wine.tex olm_wine.bib
	pdflatex -interaction=nonstopmode olm_wine
	bibtex olm_wine
	pdflatex -interaction=nonstopmode olm_wine
	pdflatex -interaction=nonstopmode olm_wine

clean:
	rm *.aux *.log *.out *.bbl *.blg *.dvi *.aux *.fff *.lof *.out 
