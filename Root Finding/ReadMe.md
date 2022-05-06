# False-Position Algorithm
## Created By: Gerard Garcia
### Goal:
Develop a MATLAB function which estimates the root of a given function using the false-position method.
Note: As a reference you can find the bisection algorithm from Figure 5.7 in your book and as a referene in the second problem. Don't copy it blindly, but instead try and make your own bisection method and compare it to the book solution. If you make that function first, you are well on the way to getting this assigment figured out.
### Inputs:
- func = the function being evaluated
- xl = the lower guess
- xu = the upper guess
- es = the desired relative error (should default to 0.0001%)
- maxit = the maximum number of iterations to use (should default to 200)
- varargin, . . . = any additional parameters used by the function
### Outputs:
- root = the estimated root location
- fx = the function evaluated at the root location
- ea = the approximate relative error (%)
- iter = how many iterations were performed
### Limitations:
- Requires a general idea of the root location
