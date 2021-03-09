all:
	mkdir -p __build
	cp *.bib *.tex __build
	cd __build && latexmk -shell-escape -pdf -bibtex pearl.tex

clean:
	rm -rf __build
