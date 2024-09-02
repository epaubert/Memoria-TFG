DOC := PaubertReca_Enrique_TFG.pdf
all: doc

doc: $(DOC:.tex=.pdf)

all: PaubertReca_Enrique_TFG.pdf

%.pdf: %.tex FORCE
	pdflatex $< && bibtex $* && pdflatex $< && pdflatex $<

FORCE: 


