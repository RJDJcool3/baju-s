---
title: Matrices
---

##### [[../Specialist Home - Year 11|← Specialist Home]]

### Introduction to Matrices
- Intro Video - 3Blue1Brown: 
  <iframe width="373" height="210" src="https://www.youtube.com/embed/kYB8IZa5AuE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
- Textbook → [[Cambridge Specialist.pdf#page=435|Cambridge Matrices]]
- Matrices are a rectangular arrangement of numbers into rows and columns
	- Matrices are used to represent linear transformations
		- Vectors can be thought as matrices with one column
	- Numbers can be thought as vectors with one component and thus vectors can be thought as matrices with one column
	  ![[MatricesCircle]]

### Matrix Rules
- A matrix is a rectangular array of mathematical objects (usually numbers)
	- E.g. $A = ({3\atop5}{-1\atop12}{0\atop-4})$
		- Matrices are represented with capital letters, such as $A$
	- If it has $m$ rows and $n$ columns, it is called a $m\ ×\ n$ matrix
		- The matrix above is a $2\ ×\ 3$ matrix
	- Entries in can be indexed using subscripts for the row and column
		- E.g. $a_{13} = 0$ in the matrix above
			- $1$ is the row, $3$ is the column 
			- A lower case letter is used for a term
	- Matrices are only equal if they have the same number of rows and columns and all corresponding entries are equal

### Matrix Addition and Subtraction
- Two matrices can be added or subtracted by adding or subtracting the corresponding entries
	- Example:
		- If $A = ({1\atop-2}{6\atop5})$ and $B = ({2\atop3}{-8\atop0})$
		- Then $A + B = ({1\ +\ 2\atop-2\ +\ 3}{6\ +\ (-8)\atop5\ +\ 0}) = ({3\atop1}{-2\atop5})$
	- Matrices can only be added/subtracted if they are of the same size
		- $m_1 = m_2,\ n_1 = n_2$

### The Zero Matrix
- The $m \ ×\ n$ with all entries equal to zero is called the **zero matrix** and will be denoted with $O$
- For any $m\ ×\ n$ matrix $A$ and the $m\ ×\ n$ zero matrix $O$, we have:
	- $A + O = A$ and $A + (-A) = O$

### Scalar Multiplication
- To multiply by a scalar, multiply each entry by the scalar
	- Scalars are real numbers
- Example:
	- If $A = ({1\atop-2}{6\atop5})$, then $3A = ({3\ ×\ 1\atop3\ ×\ -2}{3\ ×\ 6\atop3\ ×\ 5}) = ({3\atop-6}{18\atop15})$

### Matrix Multiplication
- Matrix multiplication is more complex than the other topics we have seem so far
	- Example of matrix multiplication:
		- Let $A = [{1\atop4}{3\atop2}]$ and $B = [{5\atop6}{1\atop0}]$
		- $A \ ×\ B = AB = [{1\atop4}{3\atop2}][{5\atop6}{1\atop0}]$
		- $[{1\ ×\ 5\ +\ 3\ ×\ 6\atop4\ ×\ 5\ +\ 2\ ×\ 6}\ {1\ ×\ 1\ +\ 3\ ×\ 0\atop4\ ×\ 1\ +\ 2\ ×\ 0}]$
		- $[{23\atop32}{1\atop4}]$
	- Matrix multiplication takes the values in $A$ going across in each row and multiplying them by the values in $B$ going down the corresponding column
		- $a_{11}\ ×\ b_{11},\ a_{12}\ ×\ b_{21}$
		- These values are added together to get the value in matrix $C$
- $A$ has dimensions $m\ ×\ n$ and $B$ has dimensions $p\ ×\ q$, if $n = p$ they can be multiplied
	- The resultant matrix is $m\ ×\ q$ in size
		- e.g. a matrix of size $2\ ×\ 3$ multiplied by a matrix $3\ ×\ 4$ will have a size of $2\ ×\ 4$, the like terms are removed similar to vector addition
	- Matrices can only be multiplied if the number or rows for $A$ = the number of columns for $B$
- The order is very important for matrix multiplication
	- $A\ ×\ B \neq B\ ×\ A$
		- e.g. let $A$ be size $2\ ×\ 3$ and $B$ be size $3\ ×\ 2$, $A\ ×\ B$ will be size $2\ ×\ 2$ but $B\ ×\ A$ will be size $3\ ×\ 3$
- We can find any value of any term in the resulting matrix using this formula:
	- $c_{ij} = a_{i1}\ b_{1j}\ +\ a_{i2}\ b_{2j}\ +\ ...$

### Identities
- Matrices whose size defined by $m\ ×\ n$ and $m = n$ are known as <span style="color:gold;">square matrices</span>
	- Their size can be denoted with $m\ ×\ m$
- These <span style="color:gold;">square matrices</span> have a special multiplicative index $I$ for each value of $m$
	- For $2\ ×\ 2$ matrices, the <span style="color:aqua;">identity matrix</span> is $[{1\atop0}{0\atop1}]$
	- An <span style="color:aqua;">identity matrix</span> is composed of only zeroes except for the diagonal line from the top left corner to the bottom right corner which is filled by ones
		- e.g. a $3\ ×\ 3$ <span style="color:aqua;">identity matrix</span> is $[\ \begin{smallmatrix}  1 & 0 & 0\\  0 & 1 & 0\\ 0 & 0 & 1  \end{smallmatrix}\ ]$
- <span style="color:aqua;">Identity matrix</span> are special because for a <span style="color:gold;">square matrix</span> of the same size, matrix multiplication in any order gives the same <span style="color:gold;">square matrix</span>
	- $AI = IA = A$

### Inverses
- Earlier we discussed the existence of identities, however, each <span style="color:gold;">square matrix</span> also has an <span style="color:orange;">inverse matrix</span> which when they are multiplied together, give the <span style="color:aqua;">identity matrix</span>
	- The inverse of a matrix $A$ is denoted as the unique matrix $A^{-1}$ with the property that $AA^{-1} = I$
		- <span style="color:orange;">Inverse matrices</span> are unique, there is only one for a given matrix and it also is the inverse for only one matrix
	-  The <u>order for inverse multiplication</u> always <u>gives the same result</u>, 
		- $\therefore AA^{-1} = A^{-1}A$
- ##### The Inverse of a $2\ ×\ 2$ Matrix:
	- If $A = [{a \atop c}{b \atop d}]$, than the inverse of $A$ ($A^{-1}$) is given by:
		- $A^{-1} = \frac{1}{ad\ -\ bc}[{d \atop -c}{-b \atop a}]$
			- $ad - bc \neq 0$
- ##### The Determinant
	- 