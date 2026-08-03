---
title: "Power domains"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Power_domains"
wikipedia_categories: ["Denotational semantics"]
related: ["[[Actor model theory]]", "[[Denotational semantics]]", "[[Denotational semantics of the Actor model]]", "[[Divergence (computer science)]]", "[[Strict function]]", "[[Unbounded nondeterminism]]"]
---

# Power domains

In denotational semantics and domain theory, power domains are domains of nondeterministic and concurrent computations.
The idea of power domains for functions is that a nondeterministic function may be described as a deterministic set-valued function, where the set contains all values the nondeterministic function can take for a given argument.  For concurrent systems, the idea is to express the set of all possible computations. 
Roughly speaking, a power domain is a domain whose elements are certain subsets of a domain. Taking this approach naively, though, often gives rise to domains that don't quite have the desired properties, and so one is led to increasingly complicated notions of the power domain. There are three common variants: the Plotkin, upper, and lower power domains. One way to understand these concepts is as free models of theories of nondeterminism.
For most of this article we use the terms "domain" and "continuous function" quite loosely, meaning respectively some kind of ordered structure and some kind of limit-preserving function. This flexibility is genuine; for example, in some concurrent systems it is natural to impose the condition that every message sent must eventually be delivered.  However, the limit of a chain of approximations in which a message was not delivered, would be a completed computation in which the message was never delivered! 
A modern reference to this subject is the chapter by Abramsky and Jung . Older references include those of Plotkin [1983, Chapter 8] and Smyth .

## Related

- [[Actor model theory]]
- [[Denotational semantics]]
- [[Denotational semantics of the Actor model]]
- [[Divergence (computer science)]]
- [[Strict function]]
- [[Unbounded nondeterminism]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Power_domains