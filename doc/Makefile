default: ms.pdf

ms.pdf: ms.tex joint.pdf
	pdflatex ms
	pdflatex ms
	pdflatex ms

joint.pdf: figures/joint.py
	python figures/joint.py

clean:
	rm ms.aux ms.log ms.pdf joint.pdf
