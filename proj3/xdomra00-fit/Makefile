proj3.pdf: proj3.tex
	latex proj3.tex
	dvips -sPAPERSIZE=a4 proj3.dvi
	latex proj3.tex
	dvips -sPAPERSIZE=a4 proj3.dvi
	ps2pdf proj3.ps  

clean:
	rm -rf proj3.dvi proj3.ps proj3.aux proj3.log proj3.out *converted-to.pdf