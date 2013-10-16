all: paper.pdf

paper.pdf: paper.tex paper.bib 
	pdflatex paper
	-bibtex paper
	pdflatex paper 
	pdflatex paper

clean:
	rm -f *.aux *.bbl *.blg *.log *.dvi *.bak *~ \
		paper.ps paper.pdf

