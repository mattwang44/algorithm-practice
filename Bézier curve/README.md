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
### Compile
A executable binary file named "build" will be generated.
``` 
# If GNUplot is installed, generates the output file and resulting graph.
make
```
or
```
# GNUplot not installed, resulting graph will not be generated.
make noGraph
```
### Execute
```
./build <input_file> <output_file>
```
## Demo
Test 1: [input](https://github.com/mattwang44/algorithm-practice/blob/master/B%C3%A9zier%20curve/Sample%20Input/test.in) & [output](https://github.com/mattwang44/algorithm-practice/blob/master/Bézier%20curve/Sample%20Output/test.out)  
<p style="text-align:center"><img src="./Sample Output/test.in.jpg" width="380"></p>  

Test 2: [input](https://github.com/mattwang44/algorithm-practice/blob/master/B%C3%A9zier%20curve/Sample%20Input/test_5x5.in) & [output](https://github.com/mattwang44/algorithm-practice/blob/master/Bézier%20curve/Sample%20Output/test_5x5.out)  
<p style="text-align:center"><img src="./Sample Output/test_5x5.in.jpg" width="380"></p> 

Test 3: [input](https://github.com/mattwang44/algorithm-practice/blob/master/B%C3%A9zier%20curve/Sample%20Input/test_7x7.in) & [output](https://github.com/mattwang44/algorithm-practice/blob/master/Bézier%20curve/Sample%20Output/test_7x7.out)  
<p style="text-align:center"><img src="./Sample Output/test_7x7.in.jpg" width="380"></p> 
