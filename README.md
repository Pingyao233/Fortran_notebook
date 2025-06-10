# Fortran_notebook
A Fortran notebook collect possible error statement and possible solution.

# Variable

## Variable dimension
1. ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) `ERROR` Rank mismatch in array reference at (1) (2/1) 
  
* ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) `SOLUTION` Define or index a variable with wrong dimension. For example, define 1d variable but using 2d index; mistake 1:10 and 1,10.

2. ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) `ERROR` Rank mismatch in argument (rank-1 and scalar)

* ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) `SOLUTION` Check if the variable is properly defined in each function and subroutine that uses this variable. For example, use a variable without defining. 

## Scope of usage
1. ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) `ERROR` Cannot change attributes of USE-associated symbol at (1)

* ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) `SOLUTION`  
