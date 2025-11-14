---
layout: post
title: Communication Complexity of Partial XOR Functions
date: 2024-10-24 11:15:00-0400
description: Vladimir Podolskii
tags: communication complexity
categories: fall-2024
giscus_comments: false
related_posts: true
toc:
  beginning: false
---

### Speaker 

Vladimir Podolskii
October 24, 2024. 


### Abstract
Boolean function F(x,y), where x and y are n-bit boolean vectors, is an XOR function if F(x,y) = f(x + y) for some function f on n input bits, where x+y is a bitwise XOR. XOR functions are relevant in communication complexity, partially for allowing the Fourier analytic techniques. Deterministic communication complexity of total XOR functions is relatively well understood. Montanaro and Osbourne (2009) observed that one-sided communication complexity of F is exactly equal to nonadaptive parity decision tree complexity of f. Hatami et al. (2018) showed that unrestricted communication complexity of F is polynomially related to parity decision tree complexity of f.

In this talk we discuss the connection between communication complexity of XOR functions and parity decision trees for partial functions. We show that in case of one-sided communication complexity, whether these measures are equal, depends on the number of undefined inputs of f. More precisely, if the number of undefined points of f is small, then one-sided communication complexity of F is still equal to nonadaptive parity decision tree complexity of f. At the same time, we provide a family of examples of partial functions f with a larger number of undefined points, such that these measures are not equal. For certain values of parameters we get an exponential gap. Our separation results translate to the case of two-sided communication complexity as well, in particular showing that the result of Hatami et al. (2018) cannot be generalized to partial functions.

Results for total XOR functions heavily rely on Boolean Fourier analysis and thus, the technique does not translate to partial functions. For the proofs of our results we build a linear algebraic framework instead. Separation results are proved through the reduction to covering codes.

The talk is based on joint work with Dmitry Sluch and is based on the following paper: https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.ICALP.2024.116
