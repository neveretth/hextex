LATEXCC=lualatex
BIBCC=biber
ENTRYPOINT=main

TMPFILES=*.blg *.bcf *.log *.xml *.bbl *.blg *.toc *.log *.pdf *.aux

main:
	$(LATEXCC) $(ENTRYPOINT)

full:
	$(LATEXCC) $(ENTRYPOINT)
	$(BIBCC) $(ENTRYPOINT)
	$(LATEXCC) $(ENTRYPOINT)

clean:
	rm $(TMPFILES)
