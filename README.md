# Practice 2015 - 01: Storing Super Suits

## Background
Iron Man stores his high-tech gear in temperature-controlled facilities all
across the world so that he can fight crime anywhere. However, he has a problem
configuring each facility, as some track temperature in Celsius and some in
Fahrenheit. He needs to write a program that converts from Fahrenheit to
Celsius, and vice versa.

The formula to convert a temperature in Fahrenheit (f ) to a temperature in Celsius (c) is:
`c = (5/9)(f − 32)`

The formula to convert a temperature in Celsius (c) to a temperature in Fahrenheit (f ) is:
`f = (9/5)c + 32`

## Description

### Input
The first line of the file will have an integer, n, which is the number of test
cases in this file.

Each test case consists of two lines. The first line will be
either “f” or “c” – designating whether the given temperature is in
Fahrenheit or Celsius, respectively. The second line will be a floating point
number representing the value to convert. This number will have at most two
digits after the decimal place. You need to convert Fahrenheit values into
Celsius, and Celsius values into Fahrenheit.

Each given temperature will be between 0 and 1000.

### Output
For each case, output the number converted to the appropriate scale on its own
line. You should not specify units, just output the value itself.

Each converted number should have exactly two digits of accuracy after
the decimal place, rounding as necessary (any value with a 5 in the
thousandths place rounds up).

## Sample
### Input
```
4
f
32
c
0
f
-40
c
-12.34
```

### Output
```
0.00
32.00
-40.00
9.79
```
