---
layout: post
title: Derandomization from Time-Space Tradeoffs
date: 2022-11-18 11:59:00-0400
description:  Oliver Korten
tags: circuits complexity
categories: fall-2022
giscus_comments: false
related_posts: true
toc:
  beginning: false
---

### Speaker 

[Oliver Korten]
November 18, 2022. 


### Abstract

A recurring challenge in the theory of pseudorandomness and circuit complexity is the explicit construction of ``incompressible strings,'' i.e. finite objects which lack a specific type of structure or simplicity. In most cases, there is an associated NP search problem which we call the ``compression problem,'' where we are given a candidate object and must either find a compressed/structured representation of it or determine that none exist. For a particular notion of compressibility, a natural question is whether an efficient algorithm for the compression problem would aide us in the construction of incompressible objects. Consider the following two instances of this question:
(1) Does an efficient algorithm for circuit minimization imply efficient constructions of hard truth tables?

(2) Does an efficient algorithm for factoring integers imply efficient constructions of large prime numbers?

In this work, we connect these kinds of questions to the long-standing challenge of proving space/time tradeoffs for Turing machines, and proving stronger separations between the RAM and 1-tape computation models. In particular, one of our main theorems shows that modest space/time tradeoffs for deterministic exponential time, or separations between basic Turing machine memory models, would imply a positive answer to both (1) and (2).
These results apply to the derandomization of a wider class of explicit construction problems, where we have some efficient compression scheme that encodes n-bit strings using n bits, and we aim to construct an n-bit string which cannot be recovered from its encoding.

Paper: https://eccc.weizmann.ac.il/report/2022/025/
