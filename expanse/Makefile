all: examples.pdf charactersheet.pdf

charactersheet.pdf: charactersheet.tex lengths.tex shapes.tex colors.tex common.tex
	latexmk -pdfxe charactersheet.tex
examples.pdf: examples.tex lengths.tex shapes.tex colors.tex common.tex
	latexmk -pdfxe examples.tex
