---
title: The Nature of Proof
---

##### [[../Specialist Home - Year 11|← Specialist Home]]

### Important Terms
- #### Sets of Numbers
	- $\mathbb{N}$ - Natural Numbers
		- Positive, whole numbers
	- $\mathbb{Z}$ - Integers
		- Positive or negative whole numbers
	- $\mathbb{Q}$ - Rational Numbers
		- Numbers that can be represented as a fraction
	- $\mathbb{R}$ - All Real Numbers
		- Numbers that are real
- #### Definitions
	- $\subseteq$ - Subset
	- **Theorem** - A statement that has been proved
	- **Conjecture** - A statement which is suspected to be true
- #### Quantifiers
	- **For all** - $\forall$
		- e.g. 'For all odd integers $n$,  $n^2$ + $1$ is even.'
		- We must prove that if $n$ is **any** an odd integer, then $n^2 + 1$ is even 
		- We must satisfy all cases to prove the statement
			- To prove → give a general argument that shows the statement is always true
			- To disprove → give example that disproves statement
	- **There exists** - $\exists$
		- e.g. 'There exists a prime number which is not odd.'
		- Proof: 2 is even and prime
		- We only need to satisfy one case to prove the statement
			- To prove → give example that satisfies condition
			- To disprove → give a general argument that shows the statement can't be true

### Proof by Induction
- [[Cambridge Specialist.pdf#page=198|Cambridge - Mathematical Induction]]
- An induction proof follows a very specific structure
	- How do we prove this statement using induction? 
		- $4^n - 1$ is divisible by $3$ for all integers $n \geq 1$
		- We can **notate this statement** as $P(n)$ where substituting $n$ with any integer replaces $n$ in the original statement
			- e.g. $P(2)$ → $4^2 - 1$ is divisible by $3$ for all integers $n \geq 1$
	- We must **prove two things**:
		1. The proposition is true when $n = 1$
			- $P(1)$ is true
		2. **If** the proposition is **true for some value of** $n$, then it **must also be true for the next value of** $n$
			- If $P(k)$ is true for some $k \geq 1$, then $P(k + 1)$ is also true
	- If we manage to prove both these propositions, we have shown that $P(1)$ is true, and that $P(k)$ is true for $k \geq 1$ then so is $P(k + 1)$
		- Hence, by the Principle of Mathematical Induction, $P(k)$ is true for all $n \geq 1$
	- [[Induction Worked Example and Qs.pdf|Induction Worked Example and Qs]]
- **Full Structure:** (Noah West)
	- <u>Define</u> $P(n)$
		- → Let $P(n)$ be that \<insert statement>
			- Do not have to define $n$ in your initial definition of $P(n)$
			- You must define the value every time you write $P(n)$
				- e.g. Let $P(k)$ be true, $k \in \mathbb{Z}$
	- <u>Bare Case</u> $P(1)$
		- → Show that $P(1)$ is true
	- <u>Inductive Assumption</u>
		- → Let $P(k)$ be true for some $k \in \mathbb{N}$
		- → Rewrite statement as if $P(k)$ is true
			- e.g. proving $6^n - 1$ is divisible by $5$, if $P(k)$ is true, then $6^k - 1 = 5m$
			- Define $m$ as an integer
	- <u>Inductive Step</u>
		- → Now consider $P(k + 1)$
			- Show that $P(k + 1)$ is true for all $P(k)$
		- → Substitution + working out
		- → Conclude $P(k + 1)$ is true
	- <u>Conclusion</u>
		- → We have shown that $P(1)$ is true, and that if $P(k)$ is true for some $k \in \mathbb{N}$ then $P(k + 1)$ is also true.
		- → By the principle of mathematical induction, $P(n)$ is true for all $n \in \mathbb{N}$
			- $n/k$ may be from a different set depending on the question
				- (e.g. an odd positive integer)