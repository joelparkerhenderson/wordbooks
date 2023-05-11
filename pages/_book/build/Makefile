# Makefile for the book
#
# If you get an error about XeLaTex, such as:
#
#     xelatex not found
#
# Then try adding it to your path, such as:
#
#     export PATH="$PATH:/Library/TeX/texbin/"
#

TOP := $(shell git rev-parse --show-toplevel)

all: book.md book.pdf

.PHONY: clean
clean:
	@echo "make clean"
	rm -f book.md
	rm -f book.pdf

.PHONY: help
help:
	@echo "book-binder:"
	@which book-binder
	@book-binder --version
	@echo "pandoc-from-markdown-to-pdf:"
	@which pandoc-from-markdown-to-pdf
	@echo "pandoc:"
	@which pandoc
	@pandoc --version
	@echo "pandoc-from-markdown-to-pdf:"
	@which pandoc-from-markdown-to-pdf

book.md:
	@echo "make book.md"
	book-binder book.yml book.md "$(TOP)/pages/README.md" "$(TOP)/pages" "https://github.com/joelparkerhenderson/wordbooks"

book.pdf:
	@echo "make book.pdf"
	pandoc-from-markdown-to-pdf book.md -o book.pdf
	rsync -av book.md  "../startup-super-terms-1.0.0.md"
	rsync -av book.pdf "../startup-super-terms-1.0.0.pdf"
