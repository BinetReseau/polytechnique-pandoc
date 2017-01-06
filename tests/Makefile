ENGINE=lualatex
TEMPLATE=../templates/x.latex

NGN=--latex-engine=$(ENGINE)
TPL=--template=$(TEMPLATE)

%.pdf: %.md $(TEMPLATE)
	pandoc $< $(NGN) $(TPL) -o $@
