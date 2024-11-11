# Overview 
* This folder contains practical 2
	* Sum.c and Conversion.c are the two files uploaded in this practical 2. These programs include mathematical operations in it, so we'll be using *math.h* library. For using this library we should need to make sure that the system is compatible for this.

* For compiling these files in sciprog we use the below commands:
	* For Sum.c:
	```bash
	gcc -o Sum Sum.c -lm
	```
	* For Conversion.c:
	```bash
	gcc -o Conversion Conversion.c -lm
	```
* For executing the programs:
	```bash
	./Sum
	```
	```bash
	./Conversion
	```

* Output of both the codes:
	* For Sum.c:
	Sum1 = 7.485478
	Sum2 = 7.485472
	Difference between the two is 0.000007

	* For Conversion.c:
	inum=6, fnum=6.000000, inum in binary=110

 
