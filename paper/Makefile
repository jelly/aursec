.PHONY: all clean

aursec.pdf: aursec.tex Literature.bib frontpage.tex security_issues.tex core_solution.tex detailedDescription/blockchain.tex detailedDescription/aursec-init.tex detailedDescription/aursec-chain.tex
	latexmk -xelatex -f aursec.tex


clean:
	latexmk -c
	rm -vf *.dvi *.log *.bbl
