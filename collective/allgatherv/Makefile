CC=mpicc
CFLAGS=-Wall -cc=icc
SRC=allgatherv.c
EXE=allgatherv

release : $(SRC)
	$(CC) -o $(EXE) $< $(CFLAGS)

.PHONY: clean

clean:
	rm -f $(EXE)