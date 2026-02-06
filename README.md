Overview-
1. Student ID Digits Used:
d1 = 0 (last digit)
d2 = 2 (second last digit)

Contents:
Personal Matrix Creation

Creates matrix A using the formula:
A = [[d1+2, d2+1],
     [2*d1, d2+2]]
A = [[2, 3],
     [0, 4]]

2. Matrix A Analysis-
Computes:
Shape: (2, 2)
Determinant: ≈ 8.0
Rank: 2
Eigenvalues: [2.0, 4.0]
Inverse: Computed since determinant ≠ 0

3. Value Change Experiment-
Creates matrix B by adding +1 to element A[1,0] (row 2, column 1):
B = [[2, 3],
     [1, 4]]

  
4. Matrix B Analysis-
Computes:
Shape: (2, 2)
Determinant: ≈ 5.0
Rank: 2
Eigenvalues: [1.0, 5.0]
Inverse: Computed since determinant ≠ 0

5.Observations & Explanations-

Determinant: Changed due to modification of a matrix element.
Rank: Remained the same because rows/columns stayed independent.
Eigenvalues: Changed as eigenvalues depend on all matrix entries.
Invertibility: Both matrices are invertible; invertibility depends on determinant magnitude (farther from zero = easier to invert).
