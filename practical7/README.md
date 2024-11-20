# Practical 7

In practical 7 we have performed two tasks. In first task, we have to find the estimate value of 'e' and the difference between the estimate value of 'e' and the true value of e.
* We can see that, as the order increases, the difference between them gets decreases to a particular value. Till the 12th order, the difference was getting decreased, but after 12th order the difference increased followed by the 13th order  and then the 14th order. Now, at the 15th order it starts decreasing again.
* The value of e becomes very small as the order increases, factorial value increases which in turn increases value exponentially. As the machine rounds up the number, there may be little errors in the value's representation in the memory.


## Compile:

## 1. Difference in estimate 'e' value and true value:

```bash
gcc -o finde finde.c -lm

```
# Output:

```bash
./finde

Please enter the required polynomial order 
1
e is estimated as 2.0000000000, with difference -7.182818e-01

./finde 
Please enter the required polynomial order 
10
e is estimated as 2.7182818011, with difference -2.731266e-08

./finde 
Please enter the required polynomial order 
12
e is estimated as 2.7182818283, with difference -1.728764e-10

./finde 
Please enter the required polynomial order 
13
e is estimated as 2.7182818288, with difference 3.447078e-10

./finde
Please enter the required polynomial order 
14
e is estimated as 2.7182818296, with difference 1.126602e-09

./finde 
Please enter the required polynomial order 
15
e is estimated as 2.7182818301, with difference 1.625527e-09
```

* In the task 2 we performed dynamic memory allocation with pointers along with array manipulation and pointer handling and freeing of the allocated memory. 

* - Function allocateaaray```(**int size**)```was used to take integers as an argument and return pointer to an allocated memory block of that many intergers.
* - Function fillwithones(**int, `*`array**, **int size**) takes a pointer to an array of integers and fills everycell of the array with a one.
* - Function printarray(**int, `*`array**, **int size**) that takes a pointer to an array of integers and prints its elements on screen.
* - Function freepointer(int *array) frees the allocated memory.

## 1. Difference in estimate 'e' value and true value:

```bash
gcc -o pointers pointers.c -lm

```
# Output:

```bash
./pointers

111111111111111

```
