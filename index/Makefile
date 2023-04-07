properly: index.tex
	pdflatex index.tex \
	&& pdflatex index.tex \
	&& evince index.pdf &

easy: index.tex
	pdflatex index.tex \
	&& evince index.pdf &

clean:
	rm ./index.aux ./index.log ./index.out

clean-all:
	rm ./index.aux ./index.log ./index.out ./index.pdf

