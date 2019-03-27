CC=mpicc
CFLAGS=-Wall -cc=icc

reduce : reduce.c
	$(CC) -o $@ $< $(CFLAGS)

.PHONY: clean

clean:
	rm -f reduce
