---
layout: post
title: Glauber Dynamics, expander graphs, and rapid mixing, a survey of problems and techniques
date: 2021-12-03 11:59:00-0400
description: S Venkitesh
tags: boolean_function_analysis compleixty
categories: fall-2021
giscus_comments: false
related_posts: true
toc:
  beginning: true
---

### Speaker 

[S Venkitesh](https://sites.google.com/view/venkitesh/home)
December 03, 2021. 


### Abstract

Consider the following question:  Let f : {0,1}^n \to {0,1} be a Boolean function that depends on all its input variables.  (We call such a function `truly n-variate'.) What is the least degree of a real-valued multivariate polynomial P(X_1,...,X_n) that represents the function f ? Nisan and Szegedy (1994) gave the lower bound log n - O(log log n), and this was improved to a tight bound log n - O(1) (Chiarelli, Hatami and Saks, 2020).

We will explore a probabilistic analog of the above question:  Given a truly n-variate Boolean function f, what is the least degree of a real-valued `random' polynomial that agrees with f, with high probability, at every input?  This least degree is called the `probabilistic degree' of f, and is an important complexity measure for Boolean functions.  Our understanding of this complexity measure is quite weak.  For instance, we don't even know the probabilistic degree of the OR function (which takes the value 0 at the all-0s input, and 1 at every other input).  The best-known bounds put it between (log n)^{1/2 - o(1)} and O(log n) ((Harsha and Srinivasan, 2019; Beigel, Reingold, and Spielman, 1991; Tarui, 1993).

In this talk, we will give a near-optimal understanding of the probabilistic degree of truly n-variate Boolean functions, modulo our lack of understanding of the probabilistic degree of OR.  We show that if the probabilistic degree of OR is (log n)^c, then the minimum possible probabilistic degree of a truly n-variate Boolean function is at least (log n)^{c/(c+1) - o(1)}, and this bound is tight up to (log n)^{o(1)} factors.
This is a joint work with Srikanth Srinivasan.
