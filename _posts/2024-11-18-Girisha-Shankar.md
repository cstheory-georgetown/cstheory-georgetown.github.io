---
layout: post
title: Secure Auctions for Rational Parties
date: 2024-10-18 12:15:00-0400
description: Girisha Shankar
tags: cryptography
categories: fall-2024
giscus_comments: false
related_posts: true
toc:
  beginning: false
---

### Speaker 

Girisha Shankar
October 18, 2024. 


### Abstract
Sealed bid auctions are used to allocate a resource among a set of interested parties. Traditionally, auctions need the presence of a trusted auctioneer to whom the bidders provide their private bid values. Existence of such a trusted party is not an assumption easily realized in practice. Generic secure computation protocols can be used to remove a trusted party. However, generic techniques that model security using semi-honest and malicious security models are either too weak or not efficient. It should be noted that in these models, the parties are considered to be either purely honest or purely adversarial. However, in real-life we often come across parties who take part in auctions for taking care of their own interests, that is, to maximize their own utilities. Such parties can be modeled using rational cryptography as rational agents who value winning the auction more than just learning about the bids of other parties. Moreover, these parties are often privacy sensitive, wherein they would be willing to learn about other parties’ bids only if it does not result in loss of their own privacy. Such parties are reticent to form collusion. We present protocols for running first and second price auctions in a rational cryptographic setting. We also present a novel solution concept called Privacy preserving computational dominant strategy equilibrium that can be used for modeling rational cryptographic protocols beyond the auctions.
