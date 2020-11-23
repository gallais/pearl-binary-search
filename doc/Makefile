all:
	mkdir -p __build
	cp *.bib *.tex __build
	cd __build && latexmk -pdf -bibtex pearl.tex

clean:
	rm -rf __build
