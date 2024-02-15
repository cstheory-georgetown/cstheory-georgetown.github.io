---
layout: post
title: The Composition Complexity of Majority
date: 2022-11-11 11:59:00-0400
description: Victor Lecomte 
tags: complexity 
categories: fall-2022
giscus_comments: false
related_posts: true
toc:
  beginning: true
---

### Speaker 

[Victor Lecomte](https://victorlecomte.com)
November 11, 2022. 


### Abstract

In this talk, we'll look at computing majority as a composition of local functions: Maj_n = h(g_1, ..., g_m) where each g_j: {0,1}^n → {0,1} is an arbitrary function that queries only k << n variables, and h: {0,1}^m → {0,1} is an arbitrary combining function. It turns out we need m = Θ(n/k * log k) inner functions, instead of the ideal m = n/k. This recovers as a corollary (and via an entirely different proof) the best known lower bound for bounded-width branching programs for majority. It is also the first step in a plan that we propose for breaking a longstanding barrier in lower bounds for small-depth boolean circuits.

Novel aspects of our proof include sharp bounds on the information lost as computation flows through the inner functions g_j, and the bootstrapping of lower bounds for a multi-output function (Hamming weight) into lower bounds for a single-output one (majority).

Based on a joint work with Prasanna Ramakrishnan and Li-Yang Tan at Stanford.
Paper: https://arxiv.org/pdf/2205.02374.pdf
