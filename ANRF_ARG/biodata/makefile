.PHONY: biodata.pdf all clean clean-all

all: biodata.pdf

biodata.pdf: biodata.tex
	 latexmk -pdf -shell-escape -file-line-error -f biodata.tex

clean:
	latexmk -c
	$(RM) -f biodata.aux
	$(RM) -f biodata.blg
	$(RM) -f biodata.lof
	$(RM) -f biodata.log
	$(RM) -f biodata.out
	$(RM) -f biodata.toc
	$(RM) -f biodata.fls
	$(RM) -f biodata.abstract
	$(RM) -f biodata.meta

clean-all: clean
	$(RM) -f biodata.bbl

clean-purge: clean-all
	latexmk -C
