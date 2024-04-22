pdf:
	latex proj4.tex
	bibtex proj4.aux
	latex proj4.tex
	latex proj4.tex
	dvips proj4.dvi
	ps2pdf -sPAPERSIZE=a4 proj4.ps

clean:
	rm -f *.aux *.dvi *.out *.log *.bbl *.blg *.ps proj4.pdf