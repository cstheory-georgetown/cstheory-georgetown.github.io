---
layout: post
title:  Why we couldn't prove SETH hardness of CVP for even norms, Subset-SUM, and Many more!
date: 2022-09-16 11:59:00-0400
description: Rajendra Kumar
tags: cryptography fine_grained_hardness
categories: fall-2022
giscus_comments: false
related_posts: true
toc:
  beginning: true
---

### Speaker 

[Rajendra Kumar](https://sites.google.com/view/rajendrak/home)
September 16, 2021. 


### Abstract

Lattice-based cryptographic schemes have generated much interest in recent years. Their security relies on the computational hardness of problems over geometric objects called lattices. These problems have been used to build advanced cryptographic primitives such as fully homomorphic encryption, and they are believed to be resistant to quantum attacks. Given the recent advancement in quantum technologies, many institutes such as the National Institute of Standards and Technology (NIST) and European Telecommunications Standards Institute (ETSI) have initiated a process for standardization and deployment of lattice-based schemes widely over the next few years. Recently, NIST has announced lattice-based candidates (Kyber and Dilithium) as the primary algorithms for implementation.

 

The security of the lattice-based cryptosystem schemes crucially relies on the assumption that the best-known algorithms for the corresponding lattice problems cannot be significantly improved. Understanding the fine-grained hardness of these problems is one way of getting more confidence in these assumptions.

 

In this talk, I will discuss the fine-grained hardness of the lattice problems in different p-norms. Mainly, I will focus on the recent joint work with Divesh Aggarwal. Under a complexity-theoretic assumption, we show that getting any SETH-hardness for the lattice problems in the even norm is impossible by a poly-time reduction from k-SAT to CVP. We also show similar impossibility results for Subset-SUM and many other problems.
