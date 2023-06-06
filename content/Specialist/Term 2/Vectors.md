##### [← Specialist Home](Specialist%20Home%20-%20Year%2011)

### Important Links
- [Cambridge](Cambridge%20Specialist.pdf) - Chapter 17
- [Sadler](Sadler.pdf) - Chapter 3
- [[Bajay's ClassPad Guide]]
- [Vectors with Noah](Vectors_Noah.pdf)

### Vector Symbols
- $\vec{AB}$ - A vector
- $\vec{|AB|}$ - The magnitude of a vector
- $\overline{AB}$ - A line

### Addition of Vectors
- $\vec{AB} + \vec{BC} = \vec{AC}$
	- Adjacent, identical letters cancel each other out
		- e.g: $\vec{AB} + \vec{BC} + \vec{CD} + \vec{DE} = \vec{AE}$

- #### Addition of Vectors Geometrically
	- Two vectors $\vec{u}$ and $\vec{v}$ can be added together by drawing a line segment representing u from A to B and then a line segment representing v from B to C
		![](Excalidraw/AdditionofVectors|400|)
	- Using cosine rule we can find the magnitude of $\vec{u}$ + $\vec{v}$
		- $c^{2}=a^{2}+b^{2}-2ab \times cos(C)$
	- Using sine rule we can find the angles of the triangle these vectors form
		- $\frac{a}{sinA}=\frac{b}{sinB}=\frac{c}{sinC}$
		- This can allow us to find the direction of $\vec{u}$ + $\vec{v}$

### Subtraction of Vectors
- $\vec{AB} -\vec{CB} = \vec{AC}$
	- Rewrite negative vectors by reversing direction
		- e.g: $\vec{-CB} = \vec{BC}$
		- Thus $\vec{AB} - \vec{CB} = \vec{AB} + \vec{BC} = \vec{AC}$
			- It can be solved using vector addition

### Vectors in Euclidean Geometry
- *ABCD* is a parallelogram:
	![](Excalidraw/VectorsInEuclideanGeometry|400|)
- Lines of the same length are still different line segments as they have different coordinates
	- E.g: $\overline{AB} \neq \overline{DC}$  
- However vectors of the same magnitude are the same
	- E.g: $\vec{AB} = \vec{DC}$  
	- Vectors don't have a fixed location (But the things they describe might)
	- A vector is a number representation of the distance between two points

### Abstract Vectors
- Vectors can be represented abstractly as lowercase letters from either:
	- having a tilde underneath - e.g: $\underset{\sim}{a}$ 
		- For the sake of clarity, most vectors have a tilde underneath them, however from unit vectors onward, they will just be represented as $a$
	- being underlined - e.g: $\underline{a}$
	- or being in bold - e.g: **a** or $a$
- #### Mathematical Rules for Abstract Vectors
	- ##### Equality
		- Vectors are the same __if and only if__ their magnitudes ($|a|=|b|$) are equal and their directions are equal
			- Vectors with same magnitude and direction are "like" vectors
			- Vectors with same magnitude and different directions are "unlike" vectors
			-  Vectors with different magnitude and same direction are "like" vectors
			- 2 vectors that are parallel, but are in opposite direction are "unlike" vectors
	- ##### The Negative of a Vector
		- For a vector $\underset{\sim}{a}$, the vector $\underset{\sim}{-a}$ has the same magnitude but opposite direction
		- $\vec{-AB} = \vec{BA}$ 
	- ##### Scalar Multiplication
		- For a vector ($\underset{\sim}{a}$) and positive scalar (${k}$), the vector $\underset{\sim}{a}$ is the vector with the same direction as $\underset{\sim}{a}$ and same magnitude as ${k|a|}$ 
			- Given for vector $\underset{\sim}{a}$, → $\underset{\sim}{2a} = \underset{\sim}{a} + \underset{\sim}{a}$
			- For when ${k}$ is negative, ${k}\underset{\sim}{a}$ = ${k|-a|}$
	- ##### Subtracting Vectors
		- $\underset{\sim}{a} - \underset{\sim}{b}$ = $\underset{\sim}{a} + \underset{\sim}{(-b)}$
	- ##### The Zero Vector
		- The zero vector 0 has magnitude 0 and an **undefined** direction

### Vectors in Component Form
- 2D Vectors can be represented as a sum of a horizontal ${(i)}$ and vertical ${(j)}$
	- Each vector $\underset{\sim}{u}$ in the plane can be written in **component form** as $u = xi + yj$, where:
		- $i$ is the unit vector in the positive direction of the $x$-axis
		- $j$ is the unit vector in the positive direction of the $y$-axis
	- Vector $\underset{\sim}{a}$ can be written in component form → $\underset{\sim}{a}$ = $|a|\  \cos(\theta)\ i + |a|\  \sin(\theta)\ j$  
	- Vectors in <mark class="hltr-yellow">component form are equal if and only if their components are equal</mark>:
		- $ai + bj = ci + dj$ if and only if $a = c$ and $b = d$
-  Vectors in component form can be added by adding their components and simplifying
	- ${ai + bj + ci + dj = (a+c)i + (b + d)j}$
  - From component form, the magnitude of a vector can be found through pythagoras theorem
	- For $\underset{\sim}{x} = ai + bj$
		-  $|x| = \sqrt{a^2 + b^2}$

### Unit Vectors
- A unit vector is a vector of length one unit
	- Unit vectors are represented with a 'hat' → ${\hat{u}}$
	- ${\hat{u}} = \frac{u}{|u|}$ 

### Position Vectors
- Vector used to represent the position of a point relative to the origin (in the Cartesian plane when working in a 2D space)
	- $\vec{AB} = −O\vec{A} + O\vec{B}$
		- $O$ represents the origin

### Scalar Product
- The **scalar product** (also known as dot product) is an operation that takes two vectors and gives a **real number**
- $a \cdot b = a_1b_2 + a_2b_2$
	- E.g: $a = 2i + 3j, b = i - 4j$
	- $a \cdot b = (2 \ × \  1) + (3 \ × -4) = -10$
- $a \cdot b = |a||b|\cos(\theta)$
- $\cos(\theta) = \frac{a\  \cdot \ b}{|a||b|} = \frac{a_1b_1\  + \ a_2b_2}{|a||b|}$
	- This equation allows us to find the angle between two vectors
	- $\theta$ is the angle between vectors arranged tail-to-tail or nose-to-nose
	  ![](Excalidraw/ScalarProductTheta|400|)
- If $a$ or $b = 0$, then $a \cdot b = 0$
- Rules for scalar products:
	- $a \ \cdot \ b = b \ \cdot \ a$
	- $a \ \cdot \ (b\  + \ c) = a\ \cdot \ b \ +\  a \ \cdot \ c$
	- $\lambda(a\ \cdot \ b) = a\ \cdot \ (\lambda b) = (\lambda a) \ \cdot \ b$
	-  $a \ \cdot \ a = |a|^2$
	- $a$ and $b$ are **perpendicular** if and only if $a\  \cdot \ b = 0$
	- $a\  \cdot \ b = |a| |b|$ if $a$ and $b$ are **parallel** and in the **same direction**
	- $a\  \cdot \ b = -|a| |b|$ if $a$ and $b$ are **parallel** and in the **opposite direction**

### Scalar and Vector Projections
- #### Scalar Projections
	- The scalar projection of $a$ onto $b$ is the scalar component of the shadow of $a$ on $b$
	- |$a$| $\cos(\theta)$
		- If $\theta$ is obtuse then $\cos(\theta)$ is negative
			- The scalar projection will be negative
	- The original equation can be rearranged to → $\frac{a\ \cdot\ b}{|b|}$
- ### Vector Projections
	- The vector projection is the **vector** representing the shadow of $a$ on $b$
		- Thus it will have a direction/be represented in column form
	- $(a\ \cdot \ \hat{b})\hat{b}$ → projection of $a$ onto $b$
		- Also can be rewritten as → $\frac{a\ \cdot\ b}{|b|^2} \cdot b$
		- Solve the unit vector first then solve the equation
	- |$a$| $\cos(\theta)\  \hat{b}$ → Alternative formula
		- $\hat{b}$ is the unit vector in the direction of $\hat{b}$


### Geometric Proofs using Vectors
- Vector Algebra Rules:
	- $a = b$ if and only if $a$ and $b$ have the same magnitude and direction
	- $-a$ has the same magnitude as $a$ but the opposite direction
	- For a scalar $\lambda >0$, $\lambda {a}$ has magnitude $\lambda |a|$
	- If $a = \lambda{b},$ and $\lambda > 0$, $a$ and $b$ are like parallel vectors
		- Otherwise, if $\lambda<0$, $a$ and $b$ are unlike vectors
	- Vectors can be added with a triangle of vectors
	- $a − b = a + (−b)$
	-  f $\lambda$ is a scalar, then $\lambda(a + b) = \lambda{a} + \lambda{b}$
	- $a$ and $b$ are perpendicular if and only if $a\ ×  \ b = 0$

### Relative Vectors
- Using the concept of position vectors:
	- The position of vector $a$ relative to vector $b$ → $a - b$
	- The velocity of vector $a$ relative to vector $b$ → $-a + b$
	- e.g: The velocity of ship A, as seen by an observer on ship B, is 7i - 10j. The velocity of ship A, as seen by an observer on ship C, is 13i - 2j. Find the velocity of ship B as seen by an observer on C.
		- A$r$B = 7i - 10j | A$r$B = $r$A - $r$B
		- A$r$C = 13i - 2j | A$r$C = $r$A - $r$C
		- B$r$C = ? | B$r$C = $r$B - $r$C
		- $r$B - $r$C = $r$A - $r$C - ($r$A - $r$B)
			- = 13i - 2j - (7i - 10j)
			- 6i + 8j km/h

