.PHONY: full-proposal.pdf all clean clean-all

all: full-proposal.pdf

full-proposal.pdf: full-proposal.tex
	 latexmk -pdf -shell-escape -file-line-error -f full-proposal.tex

clean:
	latexmk -c
	$(RM) -f full-proposal.aux
	$(RM) -f full-proposal.blg
	$(RM) -f full-proposal.lof
	$(RM) -f full-proposal.log
	$(RM) -f full-proposal.out
	$(RM) -f full-proposal.toc
	$(RM) -f full-proposal.fls
	$(RM) -f full-proposal.fdb_latexmk

clean-all: clean
	$(RM) -f full-proposal.bbl

clean-purge: clean-all
	latexmk -C
