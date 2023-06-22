---
title: Transformations of the Plane
---

##### [[../../Specialist/Specialist Home - Year 11|← Specialist Home]]

Textbook: [[Cambridge Specialist.pdf#page=460|Cambridge - Chapter 16]]

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
	- Reflection in the line $y = x$ and $y = -x$
		- A reflection in the line $y = x$ is defined by $(x,\ y) → (y,\ x)$
			- This can be represented in matrix multiplication: $[{x' \atop y'}] = [{0 \atop 1}{\ 1 \atop 0}][{x \atop y}]$
			  ![[ReflectionOverLineYX|250]]
		- A reflection in the line $y = -x$ is defined by $(x,\ y) → (-y,\ -x)$
			- This can be represented in matrix multiplication: $[{x' \atop y'}] = [{0 \atop -1}{\ -1 \atop 0}][{x \atop y}]$
			  ![[ReflectionOverLineY-X|250]]

##### Dilations
- Dilation is the process of stretching a shape on the graph from an axis by multiplying points by a value
	- Dilation from the $y$-axis and $x$-axis
		- A dilation from the $y$-axis is defined by $(x,\ y) → (cx,\ y)$ where $c > 0$
			- The $x$-coordinate is scaled by a factor of $c$, but the $y$-coordinate is unchanged
		- A dilation from the $x$-axis is defined by $(x,\ y) → (x,\ cy)$ where $c > 0$
			- The $y$-coordinate is scaled by a factor of $c$, but the $x$-coordinate is unchanged
		- A dilation along both the $x$-axis and $y$-axis is defined by $(x, y) → (cx, dy)$ where $c$ and $d > 0$
		- If $c$ or $d$ were negative it would also involve a reflection and therefore, a pure dilation requires $c$ to be greater than $0$