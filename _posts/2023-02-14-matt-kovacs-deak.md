---
layout: post
title: Quantum Divide and Conquer
date: 2023-04-14 11:59:00-0400
description:  Matt Kovacs-Deak
tags: quantum algorithms
categories: spring-2023
giscus_comments: false
related_posts: true
toc:
  beginning: false
---

### Speaker 

[Matt Kovacs-Deak](https://quics.umd.edu/people/matt-kovacs-deak)
April 14, 2023. 


### Abstract
The divide-and-conquer framework, used extensively in classical algorithm design, recursively breaks a problem of size n into smaller subproblems (say, a many copies of size n/b each), along with some auxiliary work of cost T_aux(n), to give a recurrence relation
T(n) ≤ a T(n/b) + T_aux(n)
for the classical complexity T(n). In this talk I will describe a quantum divide-and-conquer framework that, in certain cases, yields an analogous recurrence relation
Q(n) ≤ a sqrt(Q(n/b)) + O(Q_aux(n))
that characterizes the quantum query complexity Q(n). Using this framework near-optimal quantum query complexities can be derived for various string problems, such as (i) recognizing regular languages; (ii) decision versions of String Rotation and String Suffix; and natural parameterized versions of (iii) Longest Increasing Subsequence and (iv) Longest Common Subsequence.
