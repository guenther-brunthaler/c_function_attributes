TARGETS = call_attributes.html ownership_transfer.html

.PHONY: all doc clean
.SUFFIXES: .txt .html

all doc: $(TARGETS)

clean:
	-rm $(TARGETS)

.txt.html:
	asciidoc $<
