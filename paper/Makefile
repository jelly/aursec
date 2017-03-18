.PHONY: all clean

aursec.pdf: aursec.tex Literature.bib frontpage.tex security_issues.tex
	latexmk -xelatex -f aursec.tex


clean:
	latexmk -c
	rm -vf *.dvi *.log *.bbl
