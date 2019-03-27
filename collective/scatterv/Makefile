CC=mpicc
CFLAGS=-Wall -cc=icc

scatterv : scatterv.c
	$(CC) -o $@ $< $(CFLAGS)

.PHONY: clean

clean:
	rm -f scatterv
