CC=mpicc
CFLAGS=-Wall -cc=icc

nonblocking : nonblocking.c
	$(CC) -o $@ $< $(CFLAGS)

.PHONY: clean

clean:
	rm -f nonblocking