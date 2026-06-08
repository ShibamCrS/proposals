.PHONY: pre-proposal.pdf all clean clean-all

all: pre-proposal.pdf

pre-proposal.pdf: pre-proposal.tex
	 latexmk -pdf -shell-escape -file-line-error -f pre-proposal.tex

clean:
	latexmk -c
	$(RM) -f pre-proposal.aux
	$(RM) -f pre-proposal.blg
	$(RM) -f pre-proposal.lof
	$(RM) -f pre-proposal.log
	$(RM) -f pre-proposal.out
	$(RM) -f pre-proposal.toc
	$(RM) -f pre-proposal.fls
	$(RM) -f pre-proposal.fdb_latexmk

clean-all: clean
	$(RM) -f pre-proposal.bbl

clean-purge: clean-all
	latexmk -C
