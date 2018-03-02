# Bézier curve

This is a implementation of [Bézier curve](https://en.wikipedia.org/wiki/Bézier_curve) in C++. The resulting graph can be saved as jpg using [GNUplot](http://www.gnuplot.info).


## Input & Output

### Input
1. The integer N in the first line is the total number of control points.
2. Each of following N lines records the x- & y-coordinates of the control points.
3. The integer M in last line is the number of sampling points for the curve.
```
# Sample input
5
0 300
100 300
300 500
400 100
500 0
5
```

### Output
Each of M lines records the x- & y-coordinates of the sampling points.
```
# Sample output
0.00	300.00
126.17	331.64
268.75	306.25
394.92	162.89
500.00	0.00
```
## Compile & Execution
###Compile
A executable binary file named "build" will be generated.
``` 
# If GNUplot is installed, generates the output file and resulting graph.
make
```
or
```
## GNUplot not installed, resulting graph will not be generated.
make noGraph
```
### Execute
```
./build <input_file> <output_file>
```
## Demo
Test 1: [input](/Sample Input/test.in)/[output](/Sample Input/test.out)  
![test1](/Sample Input/test.in.jpg "test1")

