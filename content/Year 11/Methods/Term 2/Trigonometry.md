---
title: Trigonometry
---

##### [[../Methods Home - Year 11|← Methods Home]] | [[../../Specialist/Specialist Home - Year 11|← Specialist Home]]

> Specialist Textbook: [[Cambridge Specialist.pdf#page=297|Cambridge Chapter 10]]
---
## Exact Values
#### Degrees - Table of Exact Values

|              | $0\degree$ | $30\degree$          | $45\degree$          | $60\degree$          | $90\degree$ |
| ------------ | ---------- | -------------------- | -------------------- | -------------------- | ----------- |
| $\sin\theta$ | $\ 0$      | $\ \frac{1}{2}$      | $\frac{1}{\sqrt{2}}$ | $\frac{\sqrt{3}}{2}$ | $\ 1$       |
| $\cos\theta$ | $\ 1$      | $\frac{\sqrt{3}}{2}$ | $\frac{1}{\sqrt{2}}$ | $\ \frac{1}{2}$      | $\ 0$       |
| $\tan\theta$ | $\ 0$      | $\frac{1}{\sqrt{3}}$ | $\ \ 1$              | $\sqrt{3}$           | $undefined$ |


#### Radians - Table of Exact Values

|              | $\ 0$   | $\ \frac{\pi}{6}$      | $\ \frac{\pi}{4}$      | $\ \frac{\pi}{3}$      | $\frac{\pi}{2}$ |
| ------------ | ----- | -------------------- | -------------------- | -------------------- | --------------- |
| $\sin\theta$ | $\ 0$ | $\ \frac{1}{2}$      | $\frac{1}{\sqrt{2}}$ | $\frac{\sqrt{3}}{2}$ | $\ 1$             |
| $\cos\theta$ | $\ 1$ | $\frac{\sqrt{3}}{2}$ | $\frac{1}{\sqrt{2}}$ | $\ \frac{1}{2}$      | $\ 0$             |
| $\tan\theta$ | $\ 0$ | $\frac{1}{\sqrt{3}}$ | $\ \ 1$              | ${\sqrt{3}}$         | $undefined$     |

## Circle Formulas

|                 | Degrees                                                                   | Radians                                         |
| --------------- | ------------------------------------------------------------------------- | ----------------------------------------------- |
| Arc Length      | $\frac{\theta}{360\degree} × \ 2{\pi}r$                               | $\frac{\theta}{2{\pi}} × \ 2{\pi}r = {\theta}r$ |
| Chord Length    | $2r\  ×\ \sin{\frac{\theta}{2}}$                                          | Is the same                                     |
| Area of Sector  | $\frac{\theta}{360\degree} × \ {\pi}r^2$                              | $\frac{r^2{\theta}}{2}$                         |
| Area of Segment | $\frac{\theta}{360\degree} × \ 2{\pi}r - \frac{r^2{\sin}{\theta}}{2}$ | $\frac{1}{2}r^2(\theta - \sin\theta)$           |

## Trigonometric Graphs
- Trigonometry equations have an infinite number of solutions since there is an infinite amount of ways to represent an angle
	- e.g. 360$\degree$ = 720$\degree$
#### Sine and Cosine Graphs
- General Formula → $y = \textcolor{#E41B17}{a}{\sin}\textcolor{#357EC7}{b}(x - \textcolor{lightgreen}{c}) + \textcolor{gold}{d}$/$y = \textcolor{#E41B17}{a}{\cos}\textcolor{#357EC7}{b}(x - \textcolor{lightgreen}{c}) + \textcolor{gold}{d}$
	- Amplitude: $\textcolor{#E41B17}{a}$ (a > 0)
	- Period: $\frac{2\pi}{\textcolor{#357EC7}{b}}$
	- Range: \[$\textcolor{#E41B17}{-a,}$ $\textcolor{#E41B17}{a}$]
	- Domain: $\mathbb{R}$
	- Horizontal shift by $\textcolor{lightgreen}{c}$
	- Vertical shift by $\textcolor{gold}{d}$
#### Tangent Graphs
- Base Graph
	![[TangentGraph|500]]
	- Repeats every $180\degree$ or $\pi$ radians
	- Vertical asymptotes at $90\degree\pm 180\degree$
	  
- General Equation: $y = \textcolor{#E41B17}{a}{\tan}\textcolor{#357EC7}{b}(x - \textcolor{lightgreen}{c}) + \textcolor{gold}{d}$
	- **Components:**
		- $a$ is the **steepness** of the graph
		- Period: $\frac{\pi}{\textcolor{#357EC7}{b}}$
			- **The base period is $\pi$**
		- Horizontal shift by $\textcolor{lightgreen}{c}$
		- Vertical shift by $\textcolor{gold}{d}$
	- **Important Properties:**
		- The period is $\frac{\pi}{b}$
		- The range is $\mathbb{R}$
		- The asymptotes have equations $x = \frac{(2k\  +\  1)\pi}{2b}$
		- The $x$-intercepts are $x$ = $\frac{k\pi}{b}$

### Complementary Relationships
- [[../Course Documents/Textbooks/Cambridge Methods (Outdated).pdf#page=444|Cambridge - Circular Functions 12L]]
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
- [[../Course Documents/Textbooks/Cambridge Methods (Outdated).pdf#page=447|Cambridge - Circular Functions 12M]]
	- Proofs in textbook
- $\sin(A \pm B) = \sin{A}\cos{B} \pm \cos{A}\sin{B}$
- $\cos(A \pm B) = \cos{A}\cos{B} \mp \sin{A}\sin{B}$
- $\tan(A \pm B) = \frac{\tan{A}\ \pm\ \tan{B}}{1\ \mp\ \tan{A}\tan{B}}$

### Double Angle Formulas
- Using addition formulas, we can derive useful expressions for $\sin(2\theta)$, $\cos(2\theta)$ and $\tan(2\theta)$
	- We know $2\theta = \theta + \theta$
	- $\therefore \cos(2\theta) = \cos(\theta + \theta)$
	- Make sure you know how to [[Methods/Term 2/Trigonometry#Complementary Relationships|convert]] between sine and cosine so you can utilise the double angle formula
- $\sin(2\theta) = 2\sin{\theta}\cos{\theta}$
	- $\sin(\theta + \theta) = \sin{\theta}\cos{\theta} + \cos{\theta}\sin{\theta}$
- $\cos(2\theta) = 1 - 2\sin^2\theta$
	- $\cos(\theta + \theta) = \cos{\theta}\cos{\theta} - \sin{\theta}\sin{\theta}$
	- $= \cos^2\theta - \sin^2\theta$
		- ($\cos^2\theta = 1 - \sin^2\theta$)
- $\tan(2\theta) = \frac{2\tan{\theta}}{1\ -\ \tan^2\theta}$
	- $\tan(\theta + \theta) = \frac{\tan{\theta}\ +\ \tan{\theta}}{1\ -\ \tan{\theta}\tan{\theta}}$

## Inverse Trigonometric Functions
- Inverse functions need to have a set range otherwise it would not be considered a function since it would not pass the vertical line test
	- This is how scientific calculators calculate a value using an inverse trig function
- **Range** of inverse graphs:
	- $\cos^{-1}$ has range {$\theta\ |\ 0 \leq \theta \leq \pi$}
	- $\sin^{-1}$ has range {$\theta\ |\ -\frac{\pi}{2} \leq \theta \leq \frac{\pi}{2}$}
	- $\tan^{-1}$ has range {$\theta\ |\ -\frac{\pi}{2} \leq \theta \leq \frac{\pi}{2}$}
- **General solutions** to trigonometric equations:
	- For $a ∈ [−1, 1]$, the general solution of the equation $\sin x = a$ is:
		- $x = 2nπ + sin^{−1} (a)$ or $x = (2n + 1)π − sin^{−1} (a)$, where $n ∈ \mathbb{Z}$
	- For $a ∈ [−1, 1]$, the general solution of the equation $\cos x = a$ is:
		- $x = 2nπ ± cos^{−1} (a)$, where $n ∈ \mathbb{Z}$
	- For $a ∈ \mathbb{R}$, the general solution of the equation $\tan x = a$ is:
		- $x = nπ + tan^{−1} (a)$, where $n ∈ \mathbb{Z}$

