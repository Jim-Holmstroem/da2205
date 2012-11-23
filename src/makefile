FILE = final_assignment

all:
	pdflatex ${FILE}.tex
	bibtex ${FILE}
	pdflatex ${FILE}.tex
	pdflatex ${FILE}.tex

fast:
	pdflatex ${FILE}.tex

run:
	evince ${FILE}.pdf

wc:
	wc -w ${FILE}.tex

clean:
	rm -f *.toc *.aux *.log *.out *.pdf *.bbl *.blg
