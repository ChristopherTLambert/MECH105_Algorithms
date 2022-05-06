# ROOT FINDING Algorithm

## Created By: Christopher Lambert

## Algorithm Explanation%   func - the function being evaluated

### Goal 
Using root finding bisection method the function finds the root of a function bounded by a lower and upper bound that the root is within.

### Inputs:
1. xl - the lower guess
2. xu - the upper guess
3. es - the desired relative error (should default to 0.0001%)
4. maxit - the maximum number of iterations to use (should default to 200)
5. varargin, . . . - any additional parameters used by the function

### Outputs
1. root - the estimated root location
2. fx - the function evaluated at the root location
3. ea - the approximate relative error (%)
4. iter - how many iterations were performed

### Limitations
- Function requires a left and right bound meaning that the user needs to know the general location of the root. 
- Bisection method has many limitations that transfer over to the Function. For example, the root can get thrown out with horizontal lines. 
