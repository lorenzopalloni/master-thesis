properly: presentation.tex
	pdflatex presentation.tex \
	&& pdflatex presentation.tex \
	&& evince presentation.pdf &

easy: presentation.tex
	pdflatex presentation.tex \
	&& evince presentation.pdf &

clean:
	rm ./presentation.log ./presentation.toc ./presentation.nav ./presentation.snm \
		./presentation.aux ./presentation.out

clean-all:
	rm ./presentation.log ./presentation.toc ./presentation.nav ./presentation.snm \
		./presentation.aux ./presentation.out ./presentation.pdf

