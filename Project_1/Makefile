all: main
	./main

main:
	ocamlopt -o main Project1.ml

clean:
	rm -f *.cmi
	rm -f *.cmx
	rm -f *.o
	rm -f main
	
.PHONY: all clean