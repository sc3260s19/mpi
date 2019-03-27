CC=mpicc
CFLAGS=-Wall -cc=icc

bcast : bcast.c
	$(CC) -o $@ $< $(CFLAGS)

.PHONY: clean

clean:
	rm -f bcast