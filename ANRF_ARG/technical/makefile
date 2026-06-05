.PHONY: anrf_format.pdf all clean clean-all

all: anrf_format.pdf

anrf_format.pdf: anrf_format.tex
	 latexmk -pdf -shell-escape -file-line-error -f anrf_format.tex

clean:
	latexmk -c
	$(RM) -f anrf_format.aux
	$(RM) -f anrf_format.blg
	$(RM) -f anrf_format.lof
	$(RM) -f anrf_format.log
	$(RM) -f anrf_format.out
	$(RM) -f anrf_format.toc
	$(RM) -f anrf_format.fls
	$(RM) -f anrf_format.fdb_latexmk

clean-all: clean
	$(RM) -f anrf_format.bbl

clean-purge: clean-all
	latexmk -C
