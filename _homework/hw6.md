---
layout: page
title: Homework 6
permalink: /homework/hw6
---

### Directions
Solve the following problems and type up your solutions.  Your solutions should be provided in one of the following formats (in order of preference)
* typed up in $$\LaTeX$$ and submitted as a PDF on Canvas
* written legibly on blank paper, scanned into a PDF and then uploaded on Canvas
* recited in a poker game to the tune of a Kenny Rogers song

If you go with the first strategy, you may wish to check out Overleaf which is a free and intuitive website for generating $$\LaTeX$$ documents online.
If you wish to use the second method and don't own a scanner at home, you can check out the numerous scanning apps available for smartphones.

**Problem 1:**  

Determine which of the following are ideals of the given rings.  Explain.

* (a) $$R = \mathbb Z[x]$$ and $$I = \{f(x)\in R: f(1) = f(2)\}$$
* (b) $$R = \mathbb Q\times\mathbb Q$$ and $$I=\{(x,x): x\in \mathbb Q\}$$
* (c) $$R = \mathbb Z_6$$ and $$I = \{0,2,4\}$$
* (d) $$R = M_n(\mathbb C)$$ and $$I = \{A\in R: \det(A) = 0\}$$

**Problem 2:**

Let $$d$$ be an integer and consider the set

$$F = \{a + b\sqrt{d} : a,b\in\mathbb Q\}.$$

* (a) Prove that $$F$$ is the image of the evaluation homomorphism

$$\phi_{\sqrt{d}}: \mathbb Q[x]\rightarrow \mathbb R.$$

In particular, this shows that $$F$$ is a ring.

* (b) Prove that $$F$$ is a field.

* (c) Assume that $$d$$ is not a perfect square.  Prove that $$F$$ is isomorphic to $$R/I$$ for $$R = \mathbb Q[x]$$ and $$I = \langle x^2-d\rangle$$

**Problem 3:**

Let $$R = \mathbb Z[x]$$ and let $$I = \langle x^2 + x + 1, 2\rangle$$.

* (a) Determine explicitly the *distinct* elements of $$R/I$$
* (b) Show that $$F = R/I$$ is a field
* (c) Prove that $$F$$ is isomorphic to $$\mathbb Z_2\oplus \mathbb Z_2$$ as a group, but *not* as a ring

**Problem 4:**

The **Weyl algebra** in one variable is the set of all linear differential operators with polynomial coefficients

$$\Omega = \{\sum_{j=0}^m a_j(x) D^j: m\geq 0,\ \ a_0(x),\dots, a_m(x)\in \mathbb R[x]\}.$$

This is a ring with the obvious addition, and with multiplication satisfying

$$Da(x) = a(x)D + a'(x),\quad D^2 a(x) = a(x)D^2 + 2a'(x)D + a''(x)$$

and more generally 

$$D^n a(x) = a(x)D^n + na'(x)D^{n-1} + \binom{n}{2}a''(x)D^{n-2} + \dots + \binom{n}{n-1}a^{(n-1)}(x)D + a^{(n)}(x).$$

where here $$f^{(\ell)}(x)$$ is the $$\ell$$'th derivative of $$f(x)$$.

In complete generality, 

$$\left(\sum_{j=0}^m a_j(x)D^j\right) \left(\sum_{k=0}^n b_k(x)D^k\right)
= \sum_{j=0}^m\sum_{k=0}^n\sum_{\ell=0}^j \binom{j}{\ell} a_j(x)b_j^{(\ell)}(x)D^{j+k-i}.$$


So for example

$$(D + x)(xD + 3x + 1) = xD^2 + (x^2 + 3x + 2)D + 3x^2 + x + 3.$$

* (a) Show that $$\Omega$$ is not commutative
* (b) Prove that the $\Omega$ is simple, ie. that the only two-sided right ideals of $$\Omega$$ are $$0$$ and $$\Omega$$


