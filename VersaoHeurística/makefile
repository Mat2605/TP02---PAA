all: main

main: main.c Headers/LeituraArquivo.h src/LeituraArquivo.c Headers/Fila.h src/Fila.c Headers/Aventureiro.h src/Aventureiro.c
	gcc main.c src/LeituraArquivo.c src/Fila.c src/Aventureiro.c -o heuristica

Linux:
	./heuristica

Windows:
	./heuristica.exe

clean:
	rm -f heuristica