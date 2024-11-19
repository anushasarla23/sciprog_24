# Practical 6

In this practical I have created two files main.c and mm.c in order to execute the matrix multiplication of the two matrices with different dimensions. 
The mm.c file contains the fuuntion for matrix multiplication.
The makefile helps us to automate the compilating process in C. 

## Compile:

## 1. main function:

```bash
gcc main.c mm.c -o matrix

```
# Execute:

```bash
./matrix

The Matrix A is:
  1  2  3  4
  2  3  4  5
  3  4  5  6
The Matrix B is:
  -1 -2 -3
   0 -1 -2
   1  0 -1
   2  1  0
The Matrix C is:
 10       0     -10
 12      -2     -16
 14      -4     -22

```
## 2. MakeFile:

```bash
CC = gcc # C Compiler
CCFLAGS = -O3
LDFLAGS = -lm

all: mmc

mmc: main.o mm.o
	$(CC) -o $@ $^ $(LDFLAGS)

mm.o: mm.c
	$(CC) -c $(CCFLAGS) $<

main.o: main.c
	$(CC) -c $(CCFLAGS) $<

clean:
	rm *.o 

```
* This makefile helps with the compilation process of C program. Whenever any modifications are made, we just need to type make and all the requied files will get executed which are mentioned in the makefile.
* "make clean" helps to clean all the .o files if necessary.   
