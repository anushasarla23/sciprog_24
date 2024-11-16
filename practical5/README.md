# Overview
* This is the fifth practical in which we have coded three programs that we will be executing.
	* The first program is to get an understanding of the scanf function.
	* The second program is for computing Fibonacci series.
	* The third program is to compute the Inverse Hyperbolic Tangent function.
## To compile:
1) Scanf:
```bash
gcc  use_scanf.c scanf -o
```

2) Fibonacci Series:
```bash
gcc fib.c fib -o -lm
```

3) Inverse Hyperbolic Tangent Function:
```bash
gcc arctanh.c arctanh -o -lm
```

## To execute:
1) Scanf: 
```bash
./scan
```

2) Fibonacci Series:
```bash
./fib
```

3) Inverse Hyperbolic Tangent Function:
```bash
./arctanh
```

## Output:

1) Scanf:
```bash
(i)
Enter an int and a double:
1
2.3
The values you entered are: 1 and 2.3

Enter an int and a double:
4
f
Problem with input
```
2) Fibonacci Series:
```bash
Please enter a positive interger
5
This fib. series is: 
0, 1 1 2 3 5
```

3) Inverse Hyperbolic Tangent Function:
```bash
./arctan

Please enter a positive real number delta: 
0.01
The diff. at x=-0.900000 is 2.4440900820
The diff. at x=-0.890000 is 2.4006461886
The diff. at x=-0.880000 is 2.3529278226
The diff. at x=-0.870000 is 2.3152921754 
The diff. at x=-0.860000 is 2.2794698634
The diff. at x=-0.850000 is 2.2394947837
The diff. at x=-0.840000 is 2.2078315337
The diff. at x=-0.830000 is 2.1774454804
The diff. at x=-0.820000 is 2.1482496053
.
.
.
.
.
.
The diff. at x=0.770000 is 0.0149408984
The diff. at x=0.780000 is 0.0388063046
The diff. at x=0.790000 is 0.0634384047
The diff. at x=0.800000 is 0.0888840933
The diff. at x=0.810000 is 0.1151934645
The diff. at x=0.820000 is 0.1482496053
The diff. at x=0.830000 is 0.1774454804
The diff. at x=0.840000 is 0.2078315337 
The diff. at x=0.850000 is 0.2394947837
The diff. at x=0.860000 is 0.2794698634
The diff. at x=0.870000 is 0.3152921754
The diff. at x=0.880000 is 0.3529278226
The diff. at x=0.890000 is 0.4006461886
```
