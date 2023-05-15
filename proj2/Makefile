ifeq ($(OS),Windows_NT)
	command = del
	adr = 
else
	command = rm
	adr = ./
endif

proj2.pdf: proj2.tex
	latex proj2.tex
	dvips -t a4 proj2.dvi
	latex proj2.tex
	dvips -t a4 proj2.dvi
	ps2pdf proj2.ps

clean:
	$(command) $(adr)proj2.dvi $(adr)proj2.ps $(adr)proj2.aux $(adr)proj2.log