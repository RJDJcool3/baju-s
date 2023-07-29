---
title: Introduction to Differential Calculus
---

##### [[../Methods Home - Year 11|← Methods Home]]

### Rates of Change
- Rates of change is the same as the gradient on a graph
	- It is the rate at which a value is increasing
- Gradient $(m)$ is $\frac{rise}{run}$
	- $m = \frac{y_2\ -\ y_1}{x_2\ -\ x_1}$
		- This equation calculates the rate of change between two points

#### Instantaneous Rate of Change
- We know how to calculate the gradient (rate of change) between two points, but what happens when we want to find the gradient at one point, known as **instantaneous rate of change**
- Lets say we are looking to find the <span style="color:gold;">instantaneous change</span> at point $a$ on the graph $f(x)$
	- Since we need two points to calculate gradient, we imagine point $b$ also on the graph of $f(x)$ as close to $a$ as possible
	- We can imagine a <span style="color:purple;">secant</span> that goes through the points $a$ and $b$, this <span style="color:purple;">secant</span> has a gradient that can be calculated traditionally, lets say the gradient is 1
	  ![[InstantaneousRateofChange|500]]
		- As we move $b$ closer to $a$, the gradient will begin to approach the true value of the instantaneous rate of change
			- This value is known as the <u>limiting value</u>
		- Through this we can estimate the instantaneous rate of change, however this is still an <u>approximation</u>
			- Using the [[Introduction to Differential Calculus#The Derivative|derivative]] we can calculate the true limiting value
	- For a function $y = f(x)$, the <span style="color:gold;">instantaneous change</span> at the point $(a, f (a))$ is the gradient of the <u>tangent line</u> to the graph of $y = f(x)$ at the point $(a, f (a))$

### The Derivative
- Textbook: [[Cambridge Methods (Outdated).pdf#page=609|Cambridge - 17C]]
- We looked at estimating the instantaneous rate of change at point $a$ by calculating the gradient between $a$ and $b$, while $b$ got closer and closer to $a$
	- Now we will examine the actual tangent at point $a$, the true **instantaneous gradient**
- The derivative is the gradient at any point for any graph
	- e.g. the derivative of $x^2$ ($f(x) = x^2$) is $2x$
	- See below for the full [[Introduction to Differential Calculus#Definition of the Derivative|definition]]

> [!hint] Derivative Notation
> 
> The derivative of $f(x)$ is $f'(x)$

##### Limit Notation
- The notation for the limit of $2x + h + 1$ as $h$ approached $0$ is ${\lim \atop h → 0}(2x\ +\ h\ +\ 1)$
- The derivative of a function with rule $f(x)$ may be found by:
	1. Finding an expression for the gradient of the line through $P(x, f(x))$ and $Q(x + h, f(x + h))$
	2. Finding the limit of this expression as $h$ approaches $0$
- Consider the function $f(x) = x^3$. By first finding the gradient of the secant through $P(2, 8)$ and $Q(2 + h, (2 + h)^3$, find the gradient of the tangent to the curve at the point $(2, 8)$.
	- Gradient of $PQ = \frac{(2\ +\ h)^2\ -\ 8}{2\ +\ h\ -\ 2}$
		- $= \frac{12h\ +\ 16h^2\ +\ h^3}{h}$
		- $= 12 + 6h + h^2$
	- The gradient of the tangent line at $(2, 8)$ is ${\lim \atop h → 0}(12\ +\ 6h\ +\ h^2) = 12$
		- Substitute $h = 0$ into the equation to find the gradient

##### Definition of the Derivative
- The **derivative** of function $f$ is denoted $f'$ and is defined by:
	- $f'(x) = {\lim \atop h → 0}\frac{f(x\ +\ h)\ -\ f(x)}{h}$
- The **tangent line** to a graph of the function $f$ at the point $(a, f(a))$ is defined to be the line through $(a, f(a))$ with gradient $f'(a)$

#### Rules for Differentiation
- There are certain rules that we observe in differentiation:
	- Constant function: If $f(x) = c$, then $f'(x) = 0$
	- Linear function: If $f (x) = mx + c$, then $f'(x) = m$
	- Multiple: If $f (x) = k \cdot g(x)$, where $k$ is a constant, then $f'(x) = k \cdot g'(x)$
		- The derivative of a number multiple is the multiple of the derivative
		- For example: if $f(x) = 5x^2$, then $f'(x) = 5(2x) = 10x$
	- Sum: If $f(x) = g(x) + h(x)$, then $f'(x) = g'(x) + h'(x)$
		The derivative of the sum is the sum of the derivatives
		For example: if $f(x) = x^2 + 2x$, then $f'(x) = 2x + 2$
	- Difference: If $f(x) = g(x) - h(x)$, then $f'(x) = g'(x) - h'(x)$
		The derivative of the difference is the difference of the derivatives
		For example: if $f(x) = x^2 - 2x$, then $f'(x) = 2x - 2$

> [!hint] The process of finding the derivative function is called differentiation

##### Other Important Observations:
- For $f(x) = x^n → f'(x) = nx^{n-1}$ , where $n$ is a non-zero integer
	- This also works for negative powers
		- e.g. $f(x) = x^{-3} → f'(x) = -3x^{-4}$
- For $f(x) = c → f'(x) = 0$, where $c$ is a constant


>[!example]+ Alternative Notation
>
>- **Lagrange Notation**
>	- The derivative of $f(x)$ is written as $f'(x)$
>- **Leibniz Notation**
>	- The derivative of $y = f(x)$ is written as $\frac{dy}{dx}$


### Graphs of the Derivative Function
- Textbook: [[Cambridge Methods (Outdated).pdf#page=627|Cambridge 17F]]

>[!note]+ Estimating a Derivative Graph of a Polynomial Function
>
> The graph of a derivative function for a **polynomial** will be the same as the polynomial graph of one less power
> - e.g. the graph of $f'(x)$ when $f(x) = 2x^3 + 5x$ will be a parabola since the original function graph was a cubic

##### Increasing and Decreasing Functions
- A function $f$ is **strictly increasing** on an interval if $x_2 > x_1$ implies $f(x_2) > f(x_1)$
	- Strictly increasing means that the gradient <u>cannot be negative</u> at any point
		- $f'(x)$ can be $0$, as seen at the turning point in a cubic function
	- If $f'(x) > 0$ for all $x$ in the interval, then the function is strictly increasing
- A function $f$ is **strictly decreasing** on an interval if $x_2 > x_1$ implies $f(x_2) < f(x_1)$
	- Strictly decreasing means that the gradient <u>cannot be positive</u> at any point
		- $f'(x)$ can still be $0$ as explained above
	- If $f'(x) < 0$ for all $x$ in the interval, then the function is strictly decreasing

### Antiderivatives
- [[Cambridge Methods (Outdated).pdf#page=635|Cambridge - 17G]]
- The process of <u>finding a function</u> from its **derivative** is known as *antidifferentiation*
	- e.g. the **antiderivative** for $f'(x) = 2x$ is $f(x) = x^2 + c$
		- The constant $c$ is what differs all possible functions for the derivative function $f'(x) = 2x$
	- There always are multiple antiderivatives for any function
- **Integral** Symbol - $\int$
	- <u>Leibniz notation</u> can be used to state the **general antiderivative**
		- e.g. $\int\ 2x\ dx = x^2 + c$
			- The **general antiderivative** <u>OR</u> **indefinite integral** of $2x$ with respect to $x$ is equal to $x^2 + c$
	- In general if $F'(x) = f(x)$, then $\int f(x)\ dx = F(x) + c$, where $c$ is an arbitrary real number
		- **General Formula**: $\int x^n\ dx = \frac{x^{n + 1}}{n\ +\ 1} + c$, $n \in \mathbb{N} \cup \{0\}$

#### Rules for Antidifferentiation
- **Sum**: $\int f(x) + g(x)\ dx = \int f(x)\ dx + \int g(x)\ dx$
- **Difference**: $\int f(x) - g(x)\ dx = \int f(x)\ dx - \int g(x)\ dx$
- **Multiple**: $\int kf(x)\ dx = k \int f(x)\ dx$, where $k \in \mathbb{R}$
	- Do not multiply $c$ by $k$

---
[[../Term 3/Applications of Differential Calculus|Continue → Applications of Differential Calculus]]
