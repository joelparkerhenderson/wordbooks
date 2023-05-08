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

TOP = $(shell git rev-parse --show-toplevel)

all: 00_book.md 00_book.pdf

.PHONY: clean
clean:
	@echo "make clean"
	rm -f _book.md
	rm -f _book.pdf

.PHONY: help
help:
	@echo "pandoc:"
	@which pandoc
	@pandoc --version
	@echo "pandoc-from-markdown-to-pdf:"
	@which pandoc-from-markdown-to-pdf

book.md:
	@echo "make book.md"
	book-binder 00_book.yml 00_book.md "$$TOP/README.md" "https://github.com/SixArm/rust-guideposts/tree/main/projects"

book.pdf:
	@echo "make book.pdf"
	pandoc-from-markdown-to-pdf 00_book.md -o 00_book.pdf
