ENGINE=lualatex
FORMAT=latex
TEMPLATE=x
TPLFILE=../templates/$(TEMPLATE).$(FORMAT)
NGN=--latex-engine=$(ENGINE)
TPL=--template=$(TPLFILE)
FMT=-t $(FORMAT)

%.pdf: %.md $(TPLFILE)
	pandoc $< $(NGN) $(TPL) $(FMT) -o $@

%.tex: %.md $(TPLFILE)
	pandoc $< $(NGN) $(TPL) $(FMT) -o $@
