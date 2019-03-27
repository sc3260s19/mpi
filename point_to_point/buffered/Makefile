CC=mpicc
CFLAGS=-Wall -cc=icc

buffered : buffered.c
	$(CC) -o $@ $< $(CFLAGS)

.PHONY: clean

clean:
	rm -f buffered