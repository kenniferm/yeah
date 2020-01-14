makepdf:
	pdflatex main
	bibtex main
	pdflatex main
	pdflatex main
clean:
	find . -type f -not \( -name 'Makefile' -or -name '*.md' -or -name '*.sty' -or -name '*.bst' -or -name '*.bib' -or -name '*.tex' -or -name '*.png' \) -delete
