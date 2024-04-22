PROJ=proj3

$(PROJ).pdf: $(PROJ).ps
	ps2pdf -sPAPERSIZE=a4 $(PROJ).ps

$(PROJ).ps: $(PROJ).dvi
	dvips -t a4 $(PROJ).dvi

$(PROJ).dvi: $(PROJ).tex
	latex $(PROJ).tex
	latex $(PROJ).tex

clean:
	rm -f $(PROJ).aux $(PROJ).dvi $(PROJ).log $(PROJ).ps $(PROJ).out $(PROJ).pdf

.PHONY: clean
