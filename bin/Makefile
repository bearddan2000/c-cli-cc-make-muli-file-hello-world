# Makefile reads top to bottom

# 'main.o' forces make to do main.o task first
main: main.o
	cc main.o greeting.o -o main

main.o: greeting.o
	cc -c main.c -o main.o

# '-L' links the header file
greeting.o:
	cc -c greeting.c -L ./greeting.h -o greeting.o
