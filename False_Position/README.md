##False Position Script

This MATLAB algorithm uses the false position method to approximate the roots of a given function. It involves bracketing the root and iteratively narrowing down the interval until an inputted stopping criterion is reached (if none is inputted, the script will run until the relative error is less than 0.0001%). The code is efficient and accurate in finding roots of non-linear equations.
---
#Function Name: falsePosition

**Inputs:
func - the function being evaluated
 - the lower guess
 - the upper guess
es - the desired relative error (should default to 0.0001%)
maxit - the maximum number of iterations to use (should default to 200)
varargin, . . . - any additional parameters used by the function

**Outputs:
root - the estimated root location
fx - the function evaluated at the root location
ea - the approximate relative error (%)
iter - how many iterations were performed
