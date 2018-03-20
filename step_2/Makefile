# I am a comment, and I want to say that the variable CC will be
# the compiler to use.
	CC=g++
# Hey!, I am comment number 2. I want to say that CFLAGS will be the
# options I'll pass to the compiler.
	CFLAGS=-c -Wall

all: hello

hello: main.o polygon.o rectangle.o triangle.o
	$(CC) main.o polygon.o rectangle.o  triangle.o -o hello

main.o: main.cpp
	$(CC) $(CFLAGS) main.cpp

polygon.o: polygon.cpp
	$(CC) $(CFLAGS) polygon.cpp

rectangle.o: rectangle.cpp
	$(CC) $(CFLAGS) rectangle.cpp

triangle.o: triangle.cpp
	$(CC) $(CFLAGS) triangle.cpp

clean:
	rm *o hello

