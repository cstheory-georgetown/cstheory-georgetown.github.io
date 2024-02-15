---
layout: post
title: Polynomial Time Byzantine Agreement with Optimal Resilience
date: 2021-10-22 11:59:00-0400
description: Seth Pettie
tags: cryptography
categories: fall-2021
giscus_comments: false
related_posts: true
toc:
  beginning: true
---

### Speaker 

(Seth Pettie)[https://web.eecs.umich.edu/~pettie/]
October 22, 2022. 


### Abstract

"One thing that distinguishes (theoretical) computer science from other
scientific disciplines is its full-throated support of a fundamentally
adversarial view of the universe.  Malicious adversaries, with
unbounded computational advantages, attempt to foil our algorithms at
every turn and destroy their quantitative guarantees.  However, there
is one strange exception to this world view and it is this: the
algorithm must accept its input as sacrosanct, and may never simply
reject its input as illegitimate.  But what if some inputs really are
illegitimate?  Is building a ""fraud detector"" for algorithms a good
idea?

In this talk I will present a protocol for asynchronous Byzantine
Agreement against the ""strongest"" adversary, which is omniscient,
computationally unbounded, and can adaptively corrupt players as the
protocol progresses. The protocol reduces Byzantine Agreement to a
coin-flipping game in which the nominal goal is to collectively flip a
fair coin, in the presence of malicious parties that attempt to fix
its outcome.  However, in the short term the malicious parties have an
insurmountable advantage.  The true goal of the game is to build a
sound ""fraud detector"" that identifies which parties are not
playing according to protocol, and ""blacklist"" them.  The final result
is a polynomial time Byzantine Agreement protocol against an adaptive,
all-knowing adversary that can corrupt up to f<n/3 players.  The
previous-best protocol against f<n/3 corruptions took exponential
time.  Moreover, the problem cannot be solved with f >= n/3
corruptions.

Joint work with Leqi Zhu and Shang-En Huang.  https://arxiv.org/abs/2206.15335."
