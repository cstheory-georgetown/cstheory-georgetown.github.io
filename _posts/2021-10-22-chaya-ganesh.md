---
layout: post
title: Simulation extractability of Fiat-Shamir transformation of multi-round protocols
date: 2021-10-22 11:59:00-0400
description: Chaya Ganesh
tags: cryptography
categories: talks-2021
giscus_comments: false
related_posts: true
toc:
  beginning: true
---

### Speaker 

Chaya Ganesh
October 22, 2021. 


### Abstract

"The Fiat--Shamir transformation turns public-coin protocols into signature schemes, non-interactive proof systems, and signatures of knowledge (SoK). We study malleability attacks against Fiat-Shamir transformed multi-round protocols. In this talk, we will look at simulation extractability of two classes of protocols:

1. Bulletproofs: We show that Bulletproofs (or any other similar multi-round proof system satisfying some form of weak unique response property) achieve simulation-extractability in the algebraic group model.
2. SRS-based SNARKs: We formally define simulation extractability for protocols in the random oracle model (ROM) which use a structured reference string (SRS). We show sufficient conditions for compiling via the Fiat--Shamir transformation public-coin multi-round interactive protocols with SRS into simulation-extractable NIZK proof systems. We consider the case where the SRS is updatable and define a strong simulation extractability notion that allows for simulated proofs with respect to an SRS to which the adversary can contribute updates.
We show that three popular universal zero knowledge SNARKs --- Plonk, Sonic, and Marlin --- are simulation extractable."
