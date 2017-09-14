
all:
	xelatex --shell-escape tutunamayanlar_excerpt.tex
	compile_pdf cover.svg -o cover.pdf
	pdfunite cover.pdf tutunamayanlar_excerpt.pdf result.pdf
