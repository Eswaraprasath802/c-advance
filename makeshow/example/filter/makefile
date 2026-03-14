OBJECT=$(wildcard src/*)
FILTER_OBJECTS=$(patsubst .c,.o,$(filter %.c,$(OBJECT)))

all:
		@echo $(filter %c,$(OBJECT))
		@echo $(FILTER_OBJECTS)