TARGET := beautified.js
SRC := all.min.js

NODEJS := nodejs
BEAUTIFY_EXEC := ../node_modules/js-beautify/js/bin/js-beautify.js
BEAUTIFY_FLAGS := --indent-with-tabs --end-with-newline

.PHONY: all
all: $(TARGET)

$(TARGET): $(SRC)
	$(NODEJS) "$(BEAUTIFY_EXEC)" $(BEAUTIFY_FLAGS) "$<" > "$@"

.PHONY: help
help:
	$(NODEJS) "$(BEAUTIFY_EXEC)" --help

.PHONY: clean
clean:
	-rm -rf $(TARGET)
