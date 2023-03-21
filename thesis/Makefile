easy: thesis.tex
	pdflatex thesis.tex \
	&& bibtex thesis \
	&& evince thesis.pdf &

properly: thesis.tex
	pdflatex thesis.tex \
	&& bibtex thesis \
	&& pdflatex thesis.tex \
	&& pdflatex thesis.tex \
	&& evince thesis.pdf &

clean:
	rm ./thesis.aux ./thesis.bbl ./thesis.blg ./thesis.brf ./thesis.lof ./thesis.log \
		./thesis.out ./thesis.toc ./chapters/*.aux

clean-all:
	rm ./thesis.aux ./thesis.bbl ./thesis.blg ./thesis.brf ./thesis.lof ./thesis.log \
		./thesis.out ./thesis.toc ./chapters/*.aux ./thesis.pdf

# properly: thesis.tex
# 	pdflatex -shell-escape thesis.tex \
# 		&& bibtex thesis \
# 		&& pdflatex -shell-escape thesis.tex \
# 		&& pdflatex -shell-escape thesis.tex \
# 		&& evince thesis.pdf &!

# easy: thesis.tex
# 	pdflatex thesis.tex \
#     && evince thesis.pdf &!

# clean:
# 	rm -i $(find ./*.* | grep --invert-match -E '*.tex|*.sh')

