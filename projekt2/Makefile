#
#Autor: Sara Skutova
#Projekt: 2. projekt do ITY
#Soubory: proj2.tex
#Darutm: 18.3.2016
#

PROJ = proj2

all: clean ity

ity: $(PROJ).tex
	latex $(PROJ).tex
	latex $(PROJ).tex
	dvips -t a4 $(PROJ).dvi
	ps2pdf $(PROJ).ps


clean:
	rm -f $(PROJ).dvi $(PROJ).ps $(PROJ).pdf $(PROJ).aux $(PROJ).log
