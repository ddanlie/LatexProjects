ifeq ($(OS),Windows_NT)
	command = del
	adr = 
else
	command = rm
	adr = ./
endif

proj3.pdf: proj3.tex
	latex proj3.tex
	latex proj3.tex
	dvips -sPAPERSIZE=a4 proj3.dvi
	ps2pdf proj3.ps  

clean:
	$(command) $(adr)proj3.dvi $(adr)proj3.ps $(adr)proj3.aux $(adr)proj3.log $(adr)proj3.out $(adr)*converted-to.pdf