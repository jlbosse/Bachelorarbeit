#GCCFLAGS = -std=c11 -Wall

main.pdf: main.tex shearlets.tex massive_two_point_function.tex thesisstyle.sty literature.bib advanced_propagator.tex
	pdflatex -interaction=nonstopmode -file-line-error-style protokoll.tex | grep ":[^:]*:"
