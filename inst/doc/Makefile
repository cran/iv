makeall:
	make makedev
	make clean

makedev:
	make iv.pdf

iv.pdf: iv.tex maia2.sty
	pdflatex iv.tex

iv.tex: iv.rnw
	R CMD Sweave iv.rnw

clean:
	rm *.tex
	rm *.aux
	rm *.log

