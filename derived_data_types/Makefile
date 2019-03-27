CC=mpicc
CFLAGS=-Wall -cc=icc

student : student.c
	$(CC) -o $@ $< $(CFLAGS)

.PHONY: clean

clean:
	rm -f student