# MATRICES Algorithm

## Created By: Christopher Lambert

## Algorithm Explanation

### Goal 
Function that returns a n x m matrix with elements that have the following values:
- The value of each element in the first row is the number of the column
- The value of each element in the first column is the number of the row
- The rest of the elements each has a value equal to the sum of the element above it and element to the left
- The function must return a sensible error if the user does not input exactly two arguments

### Inputs
- n: Number of rows in a matrix wanted to be used
- m: Number of columns in a matrix wanted to be used

### Outputs
- A: Matrix that is returned with the correct values based on the goal of the function

### Limitations
- Matrix is only two-dimensional, meaning it can only have rows and columns
- The values of rows and columns must be larger than 0
