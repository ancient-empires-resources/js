TARGET := pretty.js
SRC := all.min.js

NODEJS := nodejs
PRETTY_EXEC := ../node_modules/pretty-js/bin/pretty-js.js
PRETTY_FLAGS := --jslint --json --indent '	' --newline lf

.PHONY: all
all: $(TARGET)

$(TARGET): $(SRC)
	$(NODEJS) "$(PRETTY_EXEC)" $(PRETTY_FLAGS) "$<" > "$@"

.PHONY: help
help:
	$(NODEJS) "$(PRETTY_EXEC)" --help

.PHONY: clean
clean:
	-rm -rf $(TARGET)
