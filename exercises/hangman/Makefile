test: test.native
	@./test.native

test.native: *.ml *.mli
	@corebuild -use-ocamlfind -pkg oUnit -quiet -pkg react test.native

clean:
	rm -rf _build

.PHONY: clean
