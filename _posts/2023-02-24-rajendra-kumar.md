---
layout: post
title: Foundations of Lattice-based Cryptography
date: 2023-02-24 11:59:00-0400
description: Rajendra Kumar
tags: circuits cryptography lattices
categories: spring-2023
giscus_comments: false
related_posts: true
toc:
  beginning: false
---

### Speaker 

[Rajendra Kumar](https://sites.google.com/view/rajendrak/home)
February 24, 2023. 


### Abstract
Public key cryptography is essential for internet security, and RSA and Diffie-Hellman are the most widely used public-key cryptosystems for internet traffic. However, recent progress in building quantum computers threatens RSA and Diffie-Hellman's security, as they are vulnerable to quantum adversaries. To address this, organizations like the National Institute of Standards and Technology (NIST) and the European Telecommunications Standards Institute (ETSI) have started standardizing and deploying cryptosystems that are secure against quantum attacks. Recently,  NIST has chosen Kyber and Dilithium, lattice-based candidates, as primary algorithms for security against quantum adversaries. The security of these cryptosystems crucially relies on the assumption that the best-known algorithms for the lattice problems cannot be significantly improved.

In this talk, I will discuss the connections between the security of lattice-based cryptosystems and the hardness of lattice problems. I will talk about classical and quantum algorithms for lattice problems. I will also discuss the works on the fine-grained security of lattice-based Crypto.
