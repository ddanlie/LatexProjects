proj4.pdf: proj4.tex
	latex proj4.tex
	bibtex proj4.tex
	latex proj4.tex
	latex proj4.tex
	dvips -sPAPERSIZE=a4 proj4.dvi
	ps2pdf proj4.ps  

clean:
	proj4.dvi proj4.ps proj4.aux proj4.log proj4.out