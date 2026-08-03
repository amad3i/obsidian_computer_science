---
title: "Computationally bounded adversary"
tags: ["cs", "foundations-math", "advanced"]
domain: Foundations & Math
level: advanced
source: "https://en.wikipedia.org/wiki/Computationally_bounded_adversary"
wikipedia_categories: ["Coding theory", "Computational complexity theory"]
related: ["[[Folded Reed–Solomon code]]", "[[List decoding]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Advice (complexity)]]", "[[Algebraic geometry code]]", "[[Alternant code]]", "[[Analysis of algorithms]]", "[[Approximation algorithm]]", "[[Arbitrarily varying channel]]", "[[Asymptotic computational complexity]]"]
---

# Computationally bounded adversary

In information theory, the computationally bounded adversary problem is a different way of looking at the problem of sending data over a noisy channel. In previous models the best that could be done was ensuring correct decoding for up to d/2 errors, where d was the Hamming distance of the code. The problem with doing it this way is that it does not take into consideration the actual amount of computing power available to the adversary. Rather, it only concerns itself with how many bits of a given code word can change and still have the message decode properly. In the computationally bounded adversary model the channel – the adversary – is restricted to only being able to perform a reasonable amount of computation to decide which bits of the code word need to change. In other words, this model does not need to consider how many errors can possibly be handled, but only how many errors could possibly be introduced given a reasonable amount of computing power on the part of the adversary. Once the channel has been given this restriction it becomes possible to construct codes that are both faster to encode and decode compared to previous methods that can also handle a large number of errors.

## Related

- [[Folded Reed–Solomon code]]
- [[List decoding]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Advice (complexity)]]
- [[Algebraic geometry code]]
- [[Alternant code]]
- [[Analysis of algorithms]]
- [[Approximation algorithm]]
- [[Arbitrarily varying channel]]
- [[Asymptotic computational complexity]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Computationally_bounded_adversary