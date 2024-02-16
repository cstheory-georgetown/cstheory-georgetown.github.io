---
layout: post
title: A better-than-3 log n depth lower bound for De Morgan formulas with restrictions on top gates
date: 2022-09-23 11:59:00-0400
description: Anastasia Sofronova
tags: complexity
categories: fall-2022
giscus_comments: false
related_posts: true
toc:
  beginning: false
---

### Speaker 

[Anastasia Sofronova](http://asofronova.com)
Septmber 23,2022. 


### Abstract

The talk is about a weak variant of Karchmer-Raz-Wigderson conjecture. This is a joint work with Ivan Mihajlin. 

We prove the existence of two functions f: {0,1}^n → {0,1} and g: {0,1}^n → {0,1}^n such that f(g(x)⊕y) is not computable by depth (1 + α − ε)n formulas with (2α − ε)n layers of AND gates at the top. We do this by a top-down approach, which was only used before for depth-3 model. As an application of the result, we immediately get a simple lower bound on a modified Andreev’s function.

Our technical contribution includes combinatorial insights into structure of composition with random boolean function and introducing a notion of well-mixed sets. A set of functions is well-mixed if, when composed with a random function, it does not have subsets that agree on large fractions of inputs. We use probabilistic method to prove the existence of well-mixed sets.
