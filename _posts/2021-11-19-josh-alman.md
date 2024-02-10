---
layout: post
title: Algorithms and Barriers for Fast Matrix Multiplication
date: 2021-11-19 11:59:00-0400
description: Josh Alman
tags: matrix_muliplication complexity
categories: fall-2021
giscus_comments: false
related_posts: true
toc:
  beginning: true
---

### Speaker 

[Josh Alman](https://joshalman.com)
November 19, 2021. 


### Abstract

Matrix multiplication is one of the most basic algebraic operations. Since Strassen's surprising breakthrough algorithm from 1969, which showed that matrices can be multiplied faster than the most straightforward algorithm, algorithmic problems from nearly every area of computer science have been sped up by clever reductions to matrix multiplication. It is popularly conjectured that two n × n matrices can be multiplied in roughly O(n^2) time, but we don't yet have the algorithmic techniques needed to achieve this.

In this talk, I'll give an overview of what's known about matrix multiplication, including some exciting recent progress. I'll talk about the techniques used to design these algorithms, leading up to the fastest known algorithm for matrix multiplication, which runs in time O(n^2.37286), which I recently designed with Virginia Vassilevska Williams. I'll then describe new barrier results which help to explain why we've been stuck for so long on this problem, and describe what kinds of insights are needed for further improvements.
