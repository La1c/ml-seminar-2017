svm.pdf: svm.tex
	latexmk -pdf svm.tex

svm.tex: svm.rtex
	R -e 'library(knitr);knit("svm.rtex");'

.PHONY: clean

clean:
	latexmk -c svm.tex
	rm svm.tex
