---
layout: post
title: Criticality of AC0-formulae
date: 2023-04-17 11:59:00-0400
description:  Prahladh Harsha
tags: circuits complexity 
categories: spring-2023
giscus_comments: false
related_posts: true
toc:
  beginning: false
---

### Speaker 

[Prahladh Harsha](https://www.tcs.tifr.res.in/~prahladh/)
April 17, 2023. 


### Abstract
Hastad's celebrated switching lemma gives inverse-exponential bounds (In terms of t) on the probability that an k-DNF when hit by a p-restriction requires decision-trees of depth larger than t. The switching lemma has proved to be extremely powerful, since its discovery, leading to optimal size lower bounds for AC0-circuits [Hastad 1986] and AC0 formulae [Rossman 2015] against the parity function

More recently, the search for optimal correlation bounds against parity led to the notion of criticality [Rossman 2019]. The criticality of a Boolean function f : {0, 1}^n → {0, 1} is the minimum λ ≥ 1 such that for all positive integers t, we have

Pr_{ρ∼Rp} [ DT_depth (f|_ρ) ≥ t ] ≤ (pλ)^t

Hastad (2014) proved that size S and depth (d+1) AC0-circuits have criticality at most O((log S)^d) leading to optimal correlation bounds of AC0-circuits against parity. Rossman (2019) subsequently proved that size S and depth (d+1) AC0-formulae, which are regular (ie., all gates of the same depth have equal fan-in) have criticality at most O(((log S)/d)^d).

In this work, we strengthen and unify all the above results by proving that any (not necessarily regular) AC0-formula of size S and depth (d+1) has criticality at most O(((log S)/d)^d).
This criticality bound implies tight correlation bounds against parity, tight Fourier concentration results and improved #SAT algorithm for AC0-formulae.

[Joint work with Tulasimohan Molli and Ashutosh Shankar]
