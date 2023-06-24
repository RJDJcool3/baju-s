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
- Important note: shear transformations are not required in the course, however they are an interesting and useful transformation
	- Read about shears here: [[Cambridge Specialist.pdf#page=467|Cambridge - Shears]]
- Matrix multiplication can be thought as applying one linear transformation and then another
	- This is why the order in matrix multiplication matters
	- The transformations happen from right to left
		- e.g. $[{1 \atop 0}{0 \atop -1}][{3 \atop 0}{0 \atop 1}]$ applies the transformation of the matrix $[{3 \atop 0}{0 \atop 1}]$ first and then the transformation of $[{1 \atop 0}{0 \atop -1}]$ afterwards
		- Think of it as a transformation of the plane as seen in the 3Blue1Brown video in [[Matrices|matrices]]

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
	- Reflections in the line $y = mx$
		- Textbook: [[Cambridge Specialist.pdf#page=472|Cambridge - Reflections in the line y = mx]]
			- The textbook explains in depth how to find the reflection matrix
		- Let’s suppose that the angle between the positive direction of the $x$-axis and the line $y = mx$ is $\theta$, then $\tan\theta = m$
			- $\therefore\ y = mx = x\tan\theta$
			- The reflection matrix is $[{x' \atop y'}] = [{\cos(2\theta) \atop \sin(2\theta)}{\ \ \ \sin(2\theta) \atop -\cos(2\theta)}][{x \atop y}]$

##### Dilations
- Dilation is the process of stretching a shape on the graph from an axis by multiplying points by a value
	- Dilation from the $y$-axis and $x$-axis
		- A dilation from the $y$-axis is defined by $(x,\ y) → (cx,\ y)$ where $c > 0$
			- The $x$-coordinate is scaled by a factor of $c$, but the $y$-coordinate is unchanged
			- This can be represented in matrix multiplication: $[{x' \atop y'}] = [{c \atop 0}{0 \atop 1}][{x \atop y}]$
		- A dilation from the $x$-axis is defined by $(x,\ y) → (x,\ cy)$ where $c > 0$
			- The $y$-coordinate is scaled by a factor of $c$, but the $x$-coordinate is unchanged
			- This can be represented in matrix multiplication: $[{x' \atop y'}] = [{1 \atop 0}{0 \atop c}][{x \atop y}]$
		- A dilation along both the $x$-axis and $y$-axis is defined by $(x, y) → (cx, dy)$ where $c$ and $d > 0$
			- The $x$-coordinate is scaled by a factor of $c$, the $y$-coordinate is scaled by a factor of $d$
			- This can be represented in matrix multiplication: $[{x' \atop y'}] = [{c \atop 0}{0 \atop d}][{x \atop y}]$
		- If $c$ or $d$ were negative it would also involve a reflection and therefore, a pure dilation requires $c$ to be greater than $0$

##### Projections
- Projections are the process of projecting a point onto either the $x$-axis or $y$-axis
	- A shape is flattened into a 2D line across either access
- The transformation is defined as $(x, y) → (x, 0)$ or $(x, y) → (0, y)$
	- $(x, y) → (x, 0)$ projects onto the $x$-axis
		- This can be represented in matrix multiplication: $[{x' \atop y'}] = [{1 \atop 0}{0 \atop 0}][{x \atop y}]$
	- $(x, y) → (0, y)$ projects onto the $y$-axis
		- This can be represented in matrix multiplication: $[{x' \atop y'}] = [{0 \atop 0}{0 \atop 1}][{x \atop y}]$

##### Translations
- A translation moves all points on the plane in the same direction and by the same distance
	- A translation is defined as $(x, y) → (x + a,\ y + b)$
		- $a$ shifts the graph in the $x$-direction
		- $b$ shifts the graph in the $y$-direction
	- A translation is expressed with vector addition
		- $[{x' \atop y'}] = [{x \atop y}] + [{a \atop b}]$
		- Translations cannot be represented with matrix multiplication

##### Rotations
- A rotation moves all points around a fixed point without changing the distance from that point
	- Textbook: [[Cambridge Specialist.pdf#page=471|Cambridge - Rotations]]
	- Rotation around the origin
		- This can be represented in matrix multiplication: $[{x' \atop y'}] = [{\cos\theta \atop \sin\theta}{-\sin\theta \atop \ \ \ \cos\theta}][{x \atop y}]$
			- $\theta$ is the angle from the positive direction of the $x$-axis