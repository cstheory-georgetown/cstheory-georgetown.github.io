---
layout: post
title: Can we bypass the curse of dimensionality in private data analysis?
date: 2024-11-15 12:15:00-0400
description: Eliad Tsfadia
tags: private data analysis
categories: fall-2024
giscus_comments: false
related_posts: true
toc:
  beginning: false
---

### Speaker 

Eliad Tsfadia
November 14, 2025. 


### Abstract
Differentially private (DP) algorithms typically exhibit a significant dependence on the dimensionality of their input, as their error or sample complexity tends to grow polynomially with the dimension. This cost of dimensionality is inherent in many problems, as Bun, Ullman, and Vadhan (STOC 2014) showed that any method that achieves lower error rates is vulnerable to tracing attacks (also known as, membership inference attacks). Unfortunately, such a cost is usually too high in many real-world scenarios like training large neural networks where the number of parameters (the ambient dimension) is very high.

On the positive side, the lower bounds do not rule out the possibility of reducing the error rates for "easy" inputs. But what are "easy" inputs? And, how likely is it to see such inputs in real-world scenarios?
In this talk, I'll present a few ways to quantify "easiness" for the fundamental task of private averaging and support them with upper and lower bounds. In particular, I'll show types of properties that are sufficient and necessary for eliminating the polynomial dependency in the dimension. I'll end the talk by presenting several future research directions.

The talk is mainly based on the following three papers:
(1) FriendlyCore https://arxiv.org/abs/2110.10132 (joint with Edith Cohen, Haim Kaplan, Yishay Mansour, and Uri Stemmer, ICML 2022),
(2) https://arxiv.org/abs/2307.07604 (joint with Naty Peter and Jonathan Ullman, COLT 2024),
(3) https://arxiv.org/abs/2402.06465 (NeurIPS 2024)
