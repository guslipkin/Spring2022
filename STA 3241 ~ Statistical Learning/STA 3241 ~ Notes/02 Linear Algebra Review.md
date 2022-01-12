# 02 Linear Algebra Review

## Matrix

- A matrix is an arry of elements with rows and columns
- <img src="02 Linear Algebra Review.assets/Screen Shot 2022-01-11 at 14.23.23.png" alt="Screen Shot 2022-01-11 at 14.23.23" style="zoom:50%;" />

## Row and Column Vector

- A single row or single column is a vector of that type (row or column)

## Transpose of a Matrix

- Flip the rows and columns
- A rXc becomes cXr
- <img src="02 Linear Algebra Review.assets/Screen Shot 2022-01-11 at 14.26.07.png" alt="Screen Shot 2022-01-11 at 14.26.07" style="zoom:50%;" />

## Symetric Matrix

- If `A'==A`, the matrix is symmetric
- If `r==c`, it’s square
  - Off-diagonal elements are symmetric i.e., $a_{ij}=a_{ji}$ *for all i and j*
- <img src="02 Linear Algebra Review.assets/Screen Shot 2022-01-11 at 14.29.32.png" alt="Screen Shot 2022-01-11 at 14.29.32" style="zoom:50%;" />

## Diagonal Matrix

- <img src="02 Linear Algebra Review.assets/Screen Shot 2022-01-11 at 14.30.09.png" alt="Screen Shot 2022-01-11 at 14.30.09" style="zoom:50%;" />

- I is the identity matrix which has 1’s on the diagonal and 0’s on the off diagonal

## Matrix Addition and Subtraction

- Only possible if matrices have the same dimensions
- Addition/subtraction is the same as doing the operation on the individual elements
- Commutative property: $A\pm B=B\pm A$
- Associative property: $(C\pm B)\pm C=A\pm (B\pm C)$
- $(A\pm B)'=A'\pm B'$

## Scalar Multiplication

- If you multiply a matrix by a constant, that’s scalar multiplication
- $B=kA\implies b_{ij}=ka_{ij} \textrm{ for all i and j}$

## Matrix Multiplication

- To multiply `A` and `B`, store the result in matrix `C`
- $C=AB$
- The number of columns in `A` must be equal to the number of rows in `B`
- $C_{rXc}=A_{rXp}*B_{pXc}$
- <img src="02 Linear Algebra Review.assets/Screen Shot 2022-01-11 at 14.40.01.png" alt="Screen Shot 2022-01-11 at 14.40.01" style="zoom:50%;" />

- A `mX1` column vector multiplied by a `1Xn` row vector becomes an `mXn` matrix
- A `1Xm` row vector multiplid by a `mX1` column vector becomes a scalar
- Usually, $AB\ne BA$
- But, $kA==Ak$ if $k$ is a scalar and $A$ is a matrix
- And, $AI==IA$ if $A$ is a matrix and $I$ is the identity matrix and conformable for multiplication

## Trace of a Square Matrix

- Sum of diagonal elements
- $tr(A)=\textrm{diag}(a_{11}+a_{22}+a_{33}+...a_{nn})$
- $tr(A)=A\textrm{, if }A\textrm{ is scalar}$
- $tr(A')=tr(A)\textrm{, as }A\textrm{ is square}$
- $tr(kA)=k tr(A)\textrm{, where }k\textrm{ is a scalar}$
- $tr(I_n)=n\textrm{, trace of an identity matrix is its dimension}$
- $tr(A\pm B)=tr(A)\pm tr(B)$
- $tr(AB)=tr(BA)$

## Hilbert Matrix

- A square matrix with entries being the unit fractions
  - $H_{ij}=\frac{1}{i+j-1}$
- A 3x3 Hilbert matrix
  - <img src="02 Linear Algebra Review.assets/Screen Shot 2022-01-12 at 09.31.19.png" alt="Screen Shot 2022-01-12 at 09.31.19" style="zoom:50%;" />

## SVD of a Matrix

