---
layout: post
title: The Value of Raft
categories: distributed raft consensus
---

## Thesis:

The value of Raft goes beyond the protocol itself. By being understandable, it penetrated into the world of software practitioners. By doing so, it made a lot of people aware about the problem of consensus from an academic point of view. With that awaraness came a possible solution to the problem, a nice introduction to the field of distributed systems, and the most important thing of all: The notion that it's a hard problem. A problem that takes serious brain time to solve. That very few people get to solve, and once they do they solve it for everyone.


That you should not. Under any circumstance. Roll your own distributed protocols.

Because you'll do it wrong! Invariably! I very much doubt that, after this newfound awareness of just how hard these problems can be, a new shiny NoSQL database can come in and say that they are distributed, fault tolenrant, strongly consistent, and not backed up by a known, formally proven consensus protocol. Maybe in 2009, but not today. And this is to me one of the most valualble things in Raft.
