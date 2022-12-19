properly: abstract.tex
	pdflatex abstract.tex \
	&& pdflatex abstract.tex \
	&& evince abstract.pdf &

easy: abstract.tex
	pdflatex abstract.tex \
	&& evince abstract.pdf &

clean:
	rm ./abstract.aux ./abstract.log ./abstract.out

clean-all:
	rm ./abstract.aux ./abstract.log ./abstract.out ./abstract.pdf

