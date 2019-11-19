Report_beeler.pdf: *.tex
	latexmk -pdf Report_beeler.tex

clean:
	rm -f *.aux
	rm -f *.log
	rm -f *.spl
	rm -f *.spl
	rm -f *.bbl
	rm -f *.blg
	rm -f *.toc
	rm -f *.lof
	rm -f *.lot
	rm -f *.fls
	rm -f *.idx
	rm -f *.ilg
	rm -f *.ind
	rm -f *.out
	rm -f *.fdb_latexmk
	rm -f figures/*converted-to.pdf
	rm -f figures/*/*converted-to.pdf

cleanall: clean
	rm -f swelling.pdf

spell:
	aspell -t --home-dir=./ -c Report_beeler.tex
