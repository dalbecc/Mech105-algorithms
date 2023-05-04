# Simpson's 1/3 Rule Script
---
* This MATLAB script uses Simpson's 1/3 rule to numerically integrate a given function over a specified interval. The rule approximates the integral by dividing the interval into smaller subintervals; providing an accurate approximation of the integral with a small error margin. Additionally the algorithm will error check that the inputs are the same length,
error check that the x input is equally spaced and warn the user if the trapezoidal rule has to be used on the last interval.
---
# Function Name: Simpson
## Function Format: Simpson(x,y)
### Inputs:
 - x: The vector of equally spaced independent variable
 - y: The vector of function values with respect to x
### Outputs:
 - I: The numerical integral calculated

