CC=mpicc
CFLAGS=-Wall -cc=icc

standard : standard.c
	$(CC) -o $@ $< $(CFLAGS)

.PHONY: clean

clean:
	rm -f standard