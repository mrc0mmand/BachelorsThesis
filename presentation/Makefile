# usage: make filename.pdf
PROJ=prezentace
all: $(PROJ).pdf

$(PROJ).pdf: $(PROJ).tex
	pdflatex $<
	pdflatex $<

clean:
	rm -f $(PROJ).pdf
