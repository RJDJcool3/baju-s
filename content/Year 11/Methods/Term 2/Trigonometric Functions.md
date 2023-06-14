---
title: Trigonometric Functions
---

##### [← Methods Home](Methods%20Home%20-%20Year%2011)

### Exact Values
##### Degrees - Table of Exact Values

|              | $0\degree$ | $30\degree$          | $45\degree$          | $60\degree$          | $90\degree$ |
| ------------ | ---------- | -------------------- | -------------------- | -------------------- | ----------- |
| $\sin\theta$ | $\ 0$      | $\ \frac{1}{2}$      | $\frac{1}{\sqrt{2}}$ | $\frac{\sqrt{3}}{2}$ | $\ 1$       |
| $\cos\theta$ | $\ 1$      | $\frac{\sqrt{3}}{2}$ | $\frac{1}{\sqrt{2}}$ | $\ \frac{1}{2}$      | $\ 0$       |
| $\tan\theta$ | $\ 0$      | $\frac{1}{\sqrt{3}}$ | $\ \ 1$              | $\sqrt{3}$           | $undefined$ |


##### Radians - Table of Exact Values

|              | $\ 0$   | $\ \frac{\pi}{6}$      | $\ \frac{\pi}{4}$      | $\ \frac{\pi}{3}$      | $\frac{\pi}{2}$ |
| ------------ | ----- | -------------------- | -------------------- | -------------------- | --------------- |
| $\sin\theta$ | $\ 0$ | $\ \frac{1}{2}$      | $\frac{1}{\sqrt{2}}$ | $\frac{\sqrt{3}}{2}$ | $\ 1$             |
| $\cos\theta$ | $\ 1$ | $\frac{\sqrt{3}}{2}$ | $\frac{1}{\sqrt{2}}$ | $\ \frac{1}{2}$      | $\ 0$             |
| $\tan\theta$ | $\ 0$ | $\frac{1}{\sqrt{3}}$ | $\ \ 1$              | ${\sqrt{3}}$         | $undefined$     |

### Circle Formulas

|                 | Degrees                                                                   | Radians                                         |
| --------------- | ------------------------------------------------------------------------- | ----------------------------------------------- |
| Arc Length      | $\frac{\theta}{360\textdegree} × \ 2{\pi}r$                               | $\frac{\theta}{2{\pi}} × \ 2{\pi}r = {\theta}r$ |
| Chord Length    | $2r\  ×\ \sin{\frac{\theta}{2}}$                                          | Is the same                                     |
| Area of Sector  | $\frac{\theta}{360\textdegree} × \ {\pi}r^2$                              | $\frac{r^2{\theta}}{2}$                         |
| Area of Segment | $\frac{\theta}{360\textdegree} × \ 2{\pi}r - \frac{r^2{\sin}{\theta}}{2}$ | $\frac{1}{2}r^2(\theta - \sin\theta)$           |

### Trigonometric Graphs
- #### Sine and Cosine Graphs
	- General Formula → $y = \textcolor{#E41B17}{a}{\sin}\textcolor{#357EC7}{n}(x - \textcolor{lightgreen}{c})$/$y = \textcolor{#E41B17}{a}{\cos}\textcolor{#357EC7}{n}(x - \textcolor{lightgreen}{c})$
		- Amplitude: $\textcolor{#E41B17}{a}$ (a > 0)
		- Period: $\frac{2\pi}{\textcolor{#357EC7}{n}}$
		- Range: \[$\textcolor{#E41B17}{-a,}$ $\textcolor{#E41B17}{a}$]
		- Domain: $\mathbb{R}$
		- Horizontal shift by $\textcolor{lightgreen}{c}$
- #### Tangent Graphs
	- Base Graph
	    ![](Excalidraw/TangentGraph|500|)
		- Repeats every $180\degree$ or $\pi$ radians
		- Vertical asymptotes at $90\degree\pm 180\degree$
		  
	- General Equation: $y = a\tan(bx + c) + d$
		- Components
			- $a$ is the steepness of the graph
			- $b$ decides the period
				- **The base period is $\pi$**
				- $\frac{\pi}{b}$ is the period
			- $c$ shifts the graph horizontally
			- $d$ shifts the graph vertically
		- Important Properties:
			- The period is $\frac{\pi}{b}$
			- The range is $\mathbb{R}$
			- The asymptotes have equations $x = \frac{(2k\  +\  1)\pi}{2b}$
			- The $x$-intercepts are $x$ = $\frac{k\pi}{b}$

### Complementary Relationships
- [Cambridge 12L](Cambridge%20Methods%20(Outdated).pdf#page=444)
- From a graph of $\textcolor{#427fbb}{\sin(\theta)}$ and $\textcolor{red}{\cos(\theta)}$ we can observe that we can transform both graphs into each other by shifting them horizontally
	- $\sin(\frac{\pi}{2} + \ \theta) = \cos(\theta)$
		- The $\sin$ graph is shifted to the left
	- $\cos(\frac{\pi}{2} +\ \theta) = \textcolor{gold}{-}\sin(\theta)$
		- The $\cos$ graph is shifted to the left and is the same as the $\sin$ graph reflected over the $x$-axis
		  ​````
```desmos-graph
width=500; height=270;
top=2; bottom=-2; right=5; left=-5;
---
    y=\sin(x)
    y=\cos(x)|RED
````

### Pythagorean Identities
- $(\sin\theta^2)$ and $(\cos\theta^2)$ can be written as $\sin^2\theta$ and $\cos^2\theta$
	- $\sin^2\theta = \sin\theta * \sin\theta$
	- Write as $\sin(x)$^$2$ on ClassPad
- Since $\sin\theta$ and $\cos\theta$ represent sides of a right angled triangle inside of a circle with radius 1, using Pythagoras we know that $\sin^2\theta+\cos^2\theta = 1$
  ![[PythagoreanIdentities|450]]
	- This is known as the Pythagorean identity
	- $\textcolor{gold}{\sin^2\theta+\cos^2\theta = 1}$
	  
### Angle Sum and Difference Identities
- [Cambridge 12M](Cambridge%20Methods%20(Outdated).pdf#page=447)
	- Proofs in textbook
- $\sin(A \pm B) = \sin{A}\cos{B} \pm \cos{A}\sin{B}$
- $\cos(A \pm B) = \cos{A}\cos{B} \mp \sin{A}\sin{B}$
- $\tan(A \pm B) = \frac{\tan{A}\ \pm\ \tan{B}}{1\ \mp\ \tan{A}\tan{B}}$

### Double Angle Formulas
- Using the addition formulas, we can derive useful expressions for $\sin(2a)$, $\cos(2a)$ and $\tan(2a)$
	- We know $2a = a + a$
	- $\therefore \cos(2a) = \cos(a + a)$
- $\sin(2a) = 2\sin{a}\cos{a}$
	- $\sin(a + a) = \sin{a}\cos{a} + \cos{a}\sin{a}$
- $\cos(2a) = 1 - 2\sin^2a$
	- $\cos(a + a) = \cos{a}\cos{a} - \sin{a}\sin{a}$
	- $= \cos^2a - \sin^2a$
		- ($\cos^2a = 1 - \sin^2a$)
- $\tan(2a) = \frac{2\tan{a}}{1\ -\ \tan^2a}$
	- $\tan(a + a) = \frac{\tan{A}\ +\ \tan{A}}{1\ -\ \tan{A}\tan{A}}$
