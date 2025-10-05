PDF=main.pdf

all: pdf

pdf:
	pdflatex main.tex
	bibtex main
	pdflatex main.tex
	pdflatex main.tex

clean:
	rm -f *.aux *.bbl *.blg *.log *.out *.toc *.lof *.lot *.fls *.fdb_latexmk *.synctex.gz

arxiv:
	zip -r URF-Astro-V2-arxiv.zip main.tex refs.bib figures .arxivignore LICENSE
