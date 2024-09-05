DOC := MemoriaTFG_EnriquePaubertReca.pdf
all: doc

doc: $(DOC:.tex=.pdf)

all: MemoriaTFG_EnriquePaubertReca.pdf

%.pdf: %.tex FORCE
	pdflatex $< && bibtex $* && pdflatex $< && pdflatex $<

FORCE: 


