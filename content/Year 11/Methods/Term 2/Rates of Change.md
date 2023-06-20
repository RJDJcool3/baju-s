---
title: Rates of Change
---

##### [[../Methods Home - Year 11|← Methods Home - Year 11]]
 
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
- We looked at estimating the instantaneous rate of change at point $a$ by calculating the gradient between $a$ and $b$ while $b$ got closer and closer to $a$, now we will examine the actual tangent at point $a$, the true instantaneous gradient
- The derivative is the gradient at any point for any graph
	- e.g. the derivative of $x^2$ ($f(x) = x^2$) is $2x$