.PHONY: all clean

all: pifm pifmdma

pifm: pifm.c
	gcc -Wall -g -std=gnu99 -lm -o pifm pifm.c

pifmdma: pifmdma.c
	gcc -Wall -g -O2 -lm -o pifmdma pifmdma.c

clean:
	rm -f pifm pifmdma

