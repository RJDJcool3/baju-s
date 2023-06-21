---
title: Transformations of the Plane
---

##### [[../../Specialist/Specialist Home - Year 11|← Specialist Home]]

Textbook: [[Cambridge Specialist.pdf#page=460|Cambridge Chapter 16]]

### Linear Transformations
- Transformations in the 2D plane are ways of systematically changing all points in the plane ($x,\ y$) to a new point in the plane ($x',\ y'$)
- Linear transformations have the rule $(x,\ y) → (ax + by,\ cx + dy)$

##### Matrices and Linear Transformations
- Each ordered pair can be written as a $2\ ×\ 1$ matrix also known as a **column vector**
	- $(x,\ y) = [{x \atop y}]$
	- Now we can rewrite the linear transformation rule: $(x, y) → (ax + by,\ cx + dy)$ using matrix multiplication:
		- $[{x' \atop y'}] = A[{x \atop y}] = [{a \atop c}{b \atop d}][{x \atop y}] = [{ax\ +\ by \atop cx\ +\ dy}]$
	- Matrix transformations will involve multiplying ($x,\ y$) by a $2\ ×\ 2$ matrix
		- The resultant will still be a $2\ ×\ 1$ matrix allowing it to be plotted

##### Transforming the Unit Square
- The unit square has vertices $(0, 0), (1, 0), (0, 1)$ and $(1, 1)$
- The effect of a linear transformation can be seen by looking at the image of the unit square while applying the transformation of a matrix
	- Check out → [Desmos Unit Square](https://www.desmos.com/calculator/erl8wdtrvu)
- In the matrix of a linear transformation:
	- The first column is the image of $(1, 0)$, written as a column vector $[{1 \atop 0}]$
	- The second column is the image of $(0, 1)$, written as a column vector $[{0 \atop 1}]$

### Geometric Transformations
- Since we can transform shapes on a 2D plain using matrices, there are several important transformations that are geometric in nature

##### Reflection
- Reflection over a line maps each point in the plane to its mirror image on the other side of the line
	- Reflection over the $x$-axis and $y$-axis
		- A reflection in the $x$-axis is defined by $(x,\ y) → (x,\ −y)$
			- This can be represented in matrix multiplication: $[{x' \atop y'}] = [{1 \atop 0}{\ 0 \atop -1}][{x \atop y}]$
		- A reflection in the y-axis is defined by $(x,\ y) → (−x,\ y)$
			- This can be represented in matrix multiplication: $[{x' \atop y'}] = [{-1 \atop 0}{\ 0 \atop 1}][{x \atop y}]$