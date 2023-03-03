### Lorenzo Palloni's thesis (M.Sc. in Computer Science).

# Dependencies (tested on Ubuntu 20.04)
```sh
sudo apt install -y texlive-latex-extra
sudo apt install -y texlive-lang-italian
sudo apt install -y texlive-science
sudo apt install -y texlive-fonts-extra
```

# Build (tested on Ubuntu 20.04)
```sh
pdflatex thesis.tex \
	&& bibtex thesis \
	&& pdflatex thesis.tex \
	&& pdflatex thesis.tex \
	&& evince thesis.pdf &
```

