project.pdf: project.tex \
	abstract.tex acknowledgements.tex \
	introduction.tex methodology.tex \
	conclusion.tex future-work.tex \
	citations.bib citations.tex
	pdflatex project
	pdflatex project
	bibtex citations
	bibtex citations
	pdflatex project
	pdflatex project
	mv project.pdf /output/
#	make simpleClean
	@echo "================================================"
	@echo "All done! project.pdf has been created. - Titus"
	@echo "================================================"

simpleClean:
	rm -rf project.log project.blg project.bbl project.aux *.dvi *.lot *~

clean:
	make simpleClean
	rm -rf project.pdf
