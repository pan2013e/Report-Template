TEX      = pdflatex
FILENAME = root
SRC      = $(FILENAME).tex
DEPS     = command.tex cover.tex body/*.tex
OBJ	     = $(FILENAME).pdf
TEXFLAG  = -shell-escape -8bit

.PHONY: clean

$(OBJ): $(SRC) $(DEPS)
	$(TEX) $(TEXFLAG) $< 
	$(TEX) $(TEXFLAG) $< 

clean:
	rm -f *.log *.aux *.toc
