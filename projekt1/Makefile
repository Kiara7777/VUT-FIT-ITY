#
#Autor: Sara Skutova
#Projekt: 1. projekt do ITY
#Soubory: proj1.tex
#Darutm: 3.3.2016
#

PROJ = proj1

all: ity

ity: $(PROJ).tex
	latex $(PROJ).tex
	dvips $(PROJ).dvi
	ps2pdf $(PROJ).ps


clean:
	rm -f $(PROJ).dvi $(PROJ).ps $(PROJ).pdf $(PROJ).aux $(PROJ).log
