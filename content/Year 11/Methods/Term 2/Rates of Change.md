---
title: Rates of Change
---

##### [[../Methods Home - Year 11|← Methods Home]]
 
### Introduction to Rates of Change
- Rates of change is the same as the gradient on a graph
	- It is the rate at which a value is increasing
- Gradient $(m)$ is $\frac{rise}{run}$
	- $m = \frac{y_2\ -\ y_1}{x_2\ -\ x_1}$
		- This equation calculates the rate of change between two points

### Instantaneous Rate of Change
- We know how to calculate the gradient (rate of change) between two points, but what happens when we want to find the gradient at one point, known as **instantaneous rate of change**
- Lets say we are looking to find the <span style="color:gold;">instantaneous change</span> at point $a$ on the graph $f(x)$
	- Since we need two points to calculate gradient, we imagine point $b$ also on the graph of $f(x)$ as close to $a$ as possible
	- We can imagine a <span style="color:purple;">secant</span> that goes through the points $a$ and $b$, this <span style="color:purple;">secant</span> has a gradient that can be calculated traditionally, lets say the gradient is 1
	  ![[InstantaneousRateofChange|500]]
		- As we move $b$ closer to $a$, the gradient will begin to approach the true value of the instantaneous rate of change
			- This value is known as the <u>limiting value</u>
		- Through this we can estimate the instantaneous rate of change, however this is still an <u>approximation</u>
			- Using the [[Rates of Change#The Derivative|derivative]] we can calculate the true limiting value
	- For a function $y = f(x)$, the <span style="color:gold;">instantaneous change</span> at the point $(a, f (a))$ is the gradient of the <u>tangent line</u> to the graph of $y = f(x)$ at the point $(a, f (a))$

### The Derivative
- Textbook: [[Cambridge Methods (Outdated).pdf#page=609|Cambridge - 17C]]
- We looked at estimating the instantaneous rate of change at point $a$ by calculating the gradient between $a$ and $b$, while $b$ got closer and closer to $a$
	- Now we will examine the actual tangent at point $a$, the true **instantaneous gradient**
- The derivative is the gradient at any point for any graph
	- e.g. the derivative of $x^2$ ($f(x) = x^2$) is $2x$
	- See below for the full [[Rates of Change#Definition of the Derivative|definition]]

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