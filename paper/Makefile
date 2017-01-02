.PHONY: all clean

aursec.pdf: aursec.tex
	latexmk -xelatex -f aursec.tex


clean:
	latexmk -c
	rm -vf *.dvi *.log *.bbl
