TARGET := pretty.js
SRC := all.min.js

PRETTY_EXEC := ../node_modules/pretty-js/bin/pretty-js.js
PRETTY_FLAGS := --jslint --indent '	'

.PHONY: all
all: $(TARGET)

$(TARGET): $(SRC)
	"$(PRETTY_EXEC)" $(PRETTY_FLAGS) "$<" > "$@"

.PHONY: clean
clean:
	-rm -rf $(TARGET)
