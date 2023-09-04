---
title: Trigonometry
---
##### [[../Methods Home - Year 11|← Methods Home]] | [[../../Specialist/Specialist Home - Year 11|← Specialist Home]]

> Specialist Textbook: [[Cambridge Specialist.pdf#page=297|Cambridge Chapter 10]]
> Specialist Textbook: [[Cambridge Specialist.pdf#page=326|Cambridge Chapter 11]]
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
- General Formula → $y = \textcolor{#E41B17}{a}{\sin}(\textcolor{#357EC7}{b}(x - \textcolor{lightgreen}{c})) + \textcolor{gold}{d}$ **/** $y = \textcolor{#E41B17}{a}{\cos}(\textcolor{#357EC7}{b}(x - \textcolor{lightgreen}{c})) + \textcolor{gold}{d}$
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
	  
- General Equation: $y = \textcolor{#E41B17}{a}{\tan}(\textcolor{#357EC7}{b}(x - \textcolor{lightgreen}{c})) + \textcolor{gold}{d}$
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

## Identities
- *Identities* are expressions with an $=$ sign which are always true regardless of the value of $x$ or $\theta$
### Complementary Relationships
- [[../Course Documents/Textbooks/Cambridge Methods (Outdated).pdf#page=444|Cambridge - Circular Functions 12L]]
- From a graph of $\textcolor{#427fbb}{\sin(\theta)}$ and $\textcolor{red}{\cos(\theta)}$ we can observe that we can transform both graphs into each other by shifting them horizontally
	- $\sin(\frac{\pi}{2} \pm \ \theta) = \cos(\theta)$
		- The $\sin$ graph is shifted to the left
	- $\cos(\frac{\pi}{2} +\ \theta) = \textcolor{#00ddff}{-}\sin(\theta),$ $\cos(\frac{\pi}{2} -\ \theta) = \sin(\theta)$
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
		- Can also be rewritten as:
			- $1 + \tan^2{\theta} = \sec^2{\theta}$
			- $\cot^2{\theta} + 1 = \csc^2{\theta}$

### Angle Sum and Difference Identities
- [[../Course Documents/Textbooks/Cambridge Methods (Outdated).pdf#page=447|Cambridge - Circular Functions 12M]]
	- Proofs in textbook
- Basic Identities:
	- $\sin(A \pm B) = \sin{A}\cos{B} \pm \cos{A}\sin{B}$
	- $\cos(A \pm B) = \cos{A}\cos{B} \mp \sin{A}\sin{B}$
	- $\tan(A \pm B) = \frac{\tan{A}\ \pm\ \tan{B}}{1\ \mp\ \tan{A}\tan{B}}$
- Simplifying $a\cos{x} + b\sin{x}$:
	- $a\cos{x} + b\sin{x} = (\sqrt{a^2 + b^2})\cos(x - \alpha)$
		- $\cos{\alpha} = \frac{a}{r}$
		- $\sin{\alpha} = \frac{b}{r}$
	- $a\cos{x} + b\sin{x} = (\sqrt{a^2 + b^2})\sin(x + \beta)$
		- $\cos{\beta} = \frac{b}{r}$
		- $\sin{\beta} = \frac{a}{r}$

> [!hint] Adding 'like' graphs
> 
> Adding $y = {a_1}\sin(x)$ to $y = {a_2}\sin(x)$ equals $y = (a_1 + a_2)\sin(x)$
> - This also works for 'like' cos graphs

### Product-to-Sum and Sum-to-Product Formulas
#### Product-to-Sum Identities
- $\cos{A}\cos{B} = \frac{1}{2}(\cos(A − B) + \cos(A + B))$
- $\sin{A}\sin{B} = \frac{1}{2}(\cos(A − B) − \cos(A + B))$
- $\sin{A}\cos{B} = \frac{1}{2}(\sin(A + B) + \sin(A − B))$
#### Sum-to-Product Identities
- These are not found in the formula sheet, you must learn to derive them from the product-to-sum identities:
	- Let $P = A + B$ and $Q = A - B$
	- Then $P + Q = 2A\ \therefore\ A = \frac{P + Q}{2}$
	- And also $P - Q = 2B\ \therefore\ B = \frac{P - Q}{2}$
- $\cos{A} + \cos{B} = 2\cos(\frac{A + B}{2})\cos(\frac{A - B}{2})$
- $\cos{A} - \cos{B} = −2\sin(\frac{A + B}{2})\sin(\frac{A - B}{2})$
- $\sin{A} + \sin{B} = 2\sin(\frac{A + B}{2})\cos(\frac{A - B}{2})$
- $\sin{A} - \sin{B} = 2\sin(\frac{A - B}{2})\cos(\frac{A + B}{2})$
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

## Reciprocal Circular Functions
- Reciprocal Functions:
	- $\sec{\theta} = \frac{1}{\cos{\theta}}$
	- $\csc{\theta} = \frac{1}{\sin{\theta}}/\mathrm{cosec}\ {\theta} = \frac{1}{\sin{\theta}}$
	- $\cot{\theta} = \frac{\cos{\theta}}{\sin{\theta}}/\cot{\theta} = \frac{1}{\tan{\theta}}$
- Pythagorean Identities:
	- $1 + \tan^2{\theta} = \sec^2{\theta}$
	- $\cot^2{\theta} + 1 = \csc^2{\theta}$

### Reciprocal Circular Graphs
- The relationship between $y = f(x)$ and $y = \frac{1}{f(x)}$:
	- The $x$-intercepts becomes vertical asymptote
	- Positive values from $f(x)$ remain positive and vice-versa
		- Local minimum → local maximum and vice-versa
	- As $f(x)$ gets larger, $\frac{1}{f(x)}$ gets smaller and vice-versa
		- As $f(x) → \infty{^+}$, $\frac{1}{f(x)} → 0^+$
	- Where $f(x) = 1$, $\frac{1}{f(x)} = 1$ → the two graphs intercept
- The graph of cotangent is a reflection and translation of the graph of tangent: $\cot(x) = -\tan(x - \frac{\pi}{2})$
#### Sec Graphs
- General Equation: $y = \textcolor{#E41B17}{a}{\sec}(\textcolor{#357EC7}{b}(x - \textcolor{lightgreen}{c})) + \textcolor{gold}{d}$
	- $\textcolor{#E41B17}{a} =$ distance from line $y = 1$ and trough/peak
	- $\textcolor{#357EC7}{b} =$ (distance between troughs/peaks) $/ \frac{\pi}{2}$