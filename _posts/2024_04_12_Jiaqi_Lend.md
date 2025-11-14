---
layout: post
title: "Quantum approach to classical optimization: why bother and what to do?"
date: 2024-04-12 11:30:00-0400
description: Jiaqi Leng
tags: optimization
categories: spring-2024
giscus_comments: false
related_posts: true
toc:
  beginning: false
---

### Speaker 

Jiaqi Leng
April 12, 2024. 


### Abstract
Continuous optimization problems arise in virtually all disciplines of quantitative research, including applied mathematics, computer science, and operations research. While convex optimization has been well studied in the past decades, nonconvex optimization generally remains intractable in theory and practice. Quantum computers, an emerging technology that exploits quantum physics for information processing, could pave an unprecedented path toward nonconvex optimization.

This talk focuses on Quantum Hamiltonian Descent (QHD), a recently proposed quantum algorithm for continuous optimization. QHD is derived as the path integral of standard gradient descent (GD). It inherits the algorithmic simplicity of GD and meanwhile exhibits a drastically different behavior from GD due to the quantum interference of classical paths, especially for nonconvex optimization. Specifically, we prove that QHD can efficiently solve a family of nonconvex continuous optimization instances, each characterized by exponentially many local minima. The new mathematics of QHD, including a surprising connection between QHD and Wasserstein geometry, is yet to be understood. Beyond the standard circuit-based implementation, we also propose an analog implementation of QHD through the Hamiltonian embedding technique for sparse Hamiltonian simulation. Based on this approach, we develop an open-source software named QHDOPT, which is used in an empirical study to confirm the practical advantage of QHD for large-scale nonconvex problems.
