
program: inputdouble.o getdouble.o
	gcc inputdouble.o getdouble.o -o program -lm

inputdouble.o: inputdouble.c getdouble.h
	gcc -c inputdouble.c

getdouble.o: getdouble.c getdouble.h
	gcc -c getdouble.c
