---
layout: post
title: Demystifying the border of depth-3 algebraic circuits 
date: 2021-11-05 11:59:00-0400
description: Pranjal Dutta
tags: circuit complexity
categories: fall-2021
giscus_comments: false
related_posts: true
toc:
  beginning: false
---

### Speaker 

[Pranjal Dutta](https://sites.google.com/view/pduttashomepage)
November 05, 2021. 


### Abstract

Border complexity of polynomials plays an integral role in GCT (Geometric complexity theory) to approach P != NP. It tries to formalize the notion of ‘approximating a polynomial’ via limits (Burgisser FOCS’01). This raises the open question whether VP ?= VP; as the approximation involves exponential precision which may not be efficiently simulable. Recently (Kumar ToCT’20) proved the universal power of the border of top-fanin-2 depth-3 circuits (border-Σ^[2]ΠΣ). In this talk, we will show that the border of bounded top-fanin depth-3 circuits (border-Σ^[k]ΠΣ for constant k) is relatively easy– it can be computed by a polynomial size algebraic branching program (ABP). 

Moreover, we will show a quasipolynomial-time blackbox identity test for the same. Prior best was in PSPACE (Forbes,Shpilka STOC’18). Our de-bordering paradigm is a multi-step process; in short we call it DiDIL – divide, derive, induct, with limit. It ‘almost’ reduces border-Σ^[k]ΠΣ to special cases of read-once oblivious algebraic branching programs (ROABPs) in any-order. 

This is based on a joint work with Prateek Dwivedi (IIT Kanpur) and Nitin Saxena (IIT Kanpur), which got accepted to FOCS 2021. A preprint is also available.
