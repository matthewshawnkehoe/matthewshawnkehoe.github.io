---
title: "Computational Number Theory"
excerpt: "Computer implementation of the Riemann Siegel formula in Julia alongside various plotting and numerical programs related to the Riemann zeta function. 
<br/>
<br/>
<img src='/images/zeta_critical_line.png'>"
collection: portfolio
---
Bernhard Riemann, a German mathematician, published his now-famous paper on the investigation of prime numbers in 1859. This eight-page paper, titled "On the Number of Primes Less Than a Given Magnitude", expanded on the work of Euler, Gauss, and Dirichlet and made numerous contributions to the study of both complex and analytic function theory. One of the major claims of this work was a conjecture about the location of zeros of the Riemann zeta function. To put it simply, Riemann hypothesized that all non-trivial zeros of the Riemann zeta function must have real part equal to $1/2$ and lie inside the critical strip $0 < s < 1$. This conjecure is now known as the Riemann Hypothesis (RH). Numerous mathematicians and computer scientists have created numerical algorithms to verify the Riemann Hypothesis up to a specific height $T$. The three most famous of these numerical algorithms are:

1. Euler-Maclaurin Summation Formula
2. Riemann–Siegel Formula
3. Odlyzko–Schonhage Algorithm

This repository contains a Julia implementation of the Riemann–Siegel formula. [Github Repository](https://github.com/matthewshawnkehoe/Riemann-Zeta-Functions)