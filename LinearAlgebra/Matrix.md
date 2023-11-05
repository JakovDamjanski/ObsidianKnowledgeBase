Matrices represent efficient mathematical way to represent systems of linear equations.
The system: 
$a_{11}x_1 + a_{12}x_2 + ... + a_{1n}x_n = b_1$
$a_{21}x_1 + a_{22}x_2 + ... + a_{2n}x_n = b_2$
$...$
$a_{m1}x_1 + a_{m2}x_2 + ... + a_{mn}x_n = b_m$

can be represented as two matrices, one with coefficients, and one with results:  
![[matrices.png]]
An extended matrix is one where we append the result on the right side of the coefficient matrix, like so:
![[extended matrix.png]]


## Leading element definition:

A leading element is the first non-null element within a given row.
## Echelon form for matrices

A rectangular matrix is in an echelon form if it satisfies the following conditions: 
1. all of its non-null rows are above the rows which are null (full of zeroes and only zeroes).
2. all leading elements within a row are to the right of the leading element in the row above it.
3. all elements in the column bellow the leading element of any given row are zeroes.

If a matrix that is already in echelon form, and it satisfies the following conditions it is in a reduced echelon form:
1. The leading element in every non-null row is 1.
2. Every leading 1 is the only non-null element within its column.

## Pivot 

A Pivot is a position within the matrix A that corresponds to the leading 1 in  the reduced echelon form of matrix A. The pivot column is the column from A which contains the pivot position.

![[pivot_example.png]]


## Algorithm for reducing the number of rows in a matrix:

1. Start with the leftmost non-null column. That's the first pivot column (the pivot is at the top position).
2. If there is a 0 at that position select a row where that is not the case and switch it with the current top row.
3. Make switches to rows so that every row that begins with a 0 is bellow rows that do not begin with a 0.
4. With the Gaussian transformation, multiplying the first row by a number and adding it to every row bellow it, transform all elements bellow the pivot into zeroes. 
5. Repeat steps 1 - 4 for each submatrix (submatrix without the first column) until there are no more rows that need to be switched.

## Existence of a solution based on echelon form of the matrix: 

The following properties apply to extended matrices in echelon form:
-  If there are no rows where all of the coefficients are 0, and the corresponding results matrix row is non-null we have *at least one solution*.
- If the number of rows and the number of variables is the same we have *only one solution.*
