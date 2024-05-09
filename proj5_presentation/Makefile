LATEX=pdflatex
LATEX_OPTS=-shell-escape

TARGET=proj5.pdf
SOURCE=proj5.tex

all: $(TARGET)

$(TARGET): $(SOURCE)
	$(LATEX) $(LATEX_OPTS) $(SOURCE)
	$(LATEX) $(LATEX_OPTS) $(SOURCE)

clean:
	rm -f *.aux *.log *.nav *.out *.snm *.toc *.vrb

distclean: clean
	rm -f $(TARGET)

.PHONY: all clean distclean
