## Pseudocode for linear Algebra
~~~python
FUNCTION matrix_sum(A,B)
  Get the no of rows and columns in matrix A
  Create an empty matrix C with same dimension
  FOR each row i;
    FOR each column j;
      Set C[i][j] to the sum of A[i][j] and B[i][j]
  Return the matrix C
END FUNCTION


## Pseudocode_solution of system of equations

FUNCTION Solution(A,b):
  Create Augmented matrix :K=[a|b]
  Reduce in Row Reduced Echelon form
  Rank=no.of non zero rows of RREF
  if Rank(k)=/Rank(A):
    print(system is in consistant)
  ELSEIF:
    solve using back susbstitution
END FUNCTION  
