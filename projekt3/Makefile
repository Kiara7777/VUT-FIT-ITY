#
#Autor: Sara Skutova
#Projekt: 3. projekt do ITY
#Soubory: proj3.tex
#Darutm: 1.4.2016
#

PROJ = proj3

all: ity

ity: $(PROJ).tex
	latex $(PROJ).tex
	latex $(PROJ).tex
	dvips $(PROJ).dvi
	ps2pdf -sPAPERSIZE=a4 $(PROJ).ps


clean:
	rm -f $(PROJ).dvi $(PROJ).ps $(PROJ).pdf $(PROJ).aux $(PROJ).log
