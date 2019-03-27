CC=mpicc
CFLAGS=-Wall -cc=icc

scatter : scatter.c
	$(CC) -o $@ $< $(CFLAGS)

.PHONY: clean

clean:
	rm -f scatter
