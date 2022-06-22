all: ata

nrl: main.c utils.c
	gcc main.c utils.c -o ../ata -lexpat -Wall -lm

clean:
	rm -rf ../ata ../files ../plano.pdf ../entrada.pdf
