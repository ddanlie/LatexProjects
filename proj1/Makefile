ifeq ($(OS),Windows_NT)
	command = del
else
	command = rm
endif

proj1.pdf: proj1.tex
	pdflatex proj1.tex
	pdflatex proj1.tex

clean:
	$(command) ./proj1.aux ./proj1.log ./proj1.out