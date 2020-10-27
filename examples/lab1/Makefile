all: lab1.pdf

%.pdf: %.tex
	latexrun --latex-cmd=xelatex -o $@ $<
	# Run twice, because LaTeX.
	latexrun --latex-cmd=xelatex -o $@ $<

clean:
	$(RM) -r latex.out
	$(RM) -v lab1.pdf
