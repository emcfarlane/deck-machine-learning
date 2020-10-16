What are the inverse and transpose of a matrix?
<!--question-->

The inverse of a matrix A is denoted $A^{-1}$. Multiplying by the inverse results in the identity matrix.

A non square matrix does not have an inverse matrix. We can compute inverses of matrices in octave with the $pinv(A)$ function and in Matlab with the $inv(A)$ function. Matrices that don't have an inverse are singular or degenerate.

The transposition of a matrix is like rotating the matrix 90° in clockwise direction and then reversing it. We can compute transposition of matrices in matlab with the transpose(A) function or A':

$A = \begin{bmatrix} a & b \\ c & d \\ e & f \end{bmatrix}$

$A^T = \begin{bmatrix} a & c & e \\ b & d & f \\ \end{bmatrix}$

In other words: $A_{ij} = A^T_{ji}$
