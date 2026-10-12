CC = gcc
CFLAGS = -Iinclude

calculator: src/main.o src/calculator.o src/logger.o
	$(CC) $(CFLAGS) src/main.o src/calculator.o src/logger.o -o calculator

src/main.o: src/main.c
	$(CC) $(CFLAGS) -c src/main.c -o src/main.o

src/calculator.o: src/calculator.c
	$(CC) $(CFLAGS) -c src/calculator.c -o src/calculator.o

src/logger.o: src/logger.c
	$(CC) $(CFLAGS) -c src/logger.c -o src/logger.o

clean:
	rm -f src/*.o calculator
