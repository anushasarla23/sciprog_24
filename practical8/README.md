# Practical 8

In this practical we programmed and executed the iterative and recursive version of Euclid's alorithm to calculate the  Greatest Common Divsior (GCD) of the two positive integers. In Euclid's algorithm we calculated gcd by repeatly dividingand taking the remainder.

* In Iterative method the function calculates the GCD by repeatedly swapping the value using the temporary variable and taking the reaminder until it gets zero.

* In Recursive method the function calculates the GCD by recursively calling itself, and passing the remainder as the new divisor, until the divisor is 0.

## Compile:

## 1. GCD with user input:

```bash
gcc -o gcd gcd.c

```
# Output:

```bash
./gcd

please enter two positive integers:
5
20
Iterative_gcd(5, 20)=5
Recursive_gcd(5, 20)=5
```
## 2. GCD with 2 random integers:

* In this code instead of taking the two positive integer from the user, instead we use 2 random integers.

```bash
gcc -o gcd_random gcd_random.c

```
# Execute:

```bash
./gcd_random

Iterative_gcd(5. 3)=1
Recursive_gcd(5. 3)=1
```
