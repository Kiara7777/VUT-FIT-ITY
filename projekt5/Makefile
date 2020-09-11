#
#Autor: Sara Skutova
#Projekt: 5. projekt do ITY
#Soubory: proj3.tex
#Datum: 4.5.2016
#

PROJ = proj5

all: ity

ity: $(PROJ).tex
	latex $(PROJ).tex
	latex $(PROJ).tex
	dvips $(PROJ).dvi
	ps2pdf $(PROJ).ps


clean:
	rm -f $(PROJ).dvi $(PROJ).ps $(PROJ).pdf $(PROJ).aux $(PROJ).log $(PROJ).nav $(PROJ).out $(PROJ).snm $(PROJ).toc
