---
title: Differential and Integral Calculus
category: Mathematics
order: 1
---

## Introduction

What is \\( \displaystyle\int_{0}^{\pi}\sin(x) \mathrm{d}x \\)? It is simply
\\(-\cos(x)\\) evaluated from $x=0$ to $x=\pi$. In other words, $-\cos(\pi)-(-\cos(0))
= -1 + 1 = 0$. Something should bother you though. Why did we use antiderivatives
when solving for integrals? In order to give the reader a complete answer we will
go through one of the common constructions of integrals and derivatives.

Many students at the post-secondary level know how to differentiate and
integrate real-valued functions like $f(x)=2x+13$ and $g(x)=e^x+\sin(x)$.
We learn that the derivative at point of a function represents the instanteneous
rate of change at that point. The definite integral of a function over an
interval represents the limit of the Riemann Sums. If the function is always
positive, the limit of the Riemann Sums will represent the area underneath
the curve $f(x)$.

### Definition of an integral

Suppose $f$ is a function that has finitely many discontinuities over the
interval $[a,b]$. Consider a tagged partition of $f$ over the interval $[a,b]$;
that is, an ordered set of numbers $P=(x_0, t_1, x_1, \ldots, t_n, x_n)$
where $a=x_0 \leq t_1 < x_1 \leq \ldots \leq t_n \leq x_n$. We define the
Riemann Sum to be:
$$R(f,P)=\sum_{i=1}^nf(t_i)(x_i-x_{i-1})$$
In our example, let
$f(x)=\sin(x)$
and $P=(0,\pi/n,\pi/n,2\pi/n,2\pi/n,\ldots,(n-1)\pi/n,\pi)$.
Then, we have
$$R(\sin,P)=\sum_{i=1}^n\sin(i\pi/n)(\pi/n)$$
