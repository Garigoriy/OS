CC = gcc
CFLAGS = -pedantic -Wall -std=c11 -O2
LDFLAGS = -lpthread
EXECUTABLE = lab3
SRC=lab3.c

all:
	$(CC) $(CFLAGS) $(SRC) -o $(EXECUTABLE) $(LDFLAGS)

clean:
	rm -f *.o $(EXECUTABLE)