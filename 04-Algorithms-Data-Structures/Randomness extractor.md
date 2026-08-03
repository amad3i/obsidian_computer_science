---
title: "Randomness extractor"
tags: ["cs", "algorithms-data-structures", "advanced"]
domain: Algorithms & Data Structures
level: advanced
source: "https://en.wikipedia.org/wiki/Randomness_extractor"
wikipedia_categories: ["Computational complexity theory", "Cryptographic algorithms", "Random number generation"]
related: ["[[Randomness merger]]", "[[Bach's algorithm]]", "[[Aanderaa–Karp–Rosenberg conjecture]]", "[[Advice (complexity)]]", "[[Analysis of algorithms]]", "[[Approximation algorithm]]", "[[Asymptotic computational complexity]]", "[[Averaging argument]]", "[[B92 protocol]]", "[[BB84]]"]
---

# Randomness extractor

A randomness extractor, often simply called an "extractor", is a function, which being applied to output from a weak entropy source, together with a short, uniformly random seed, generates a highly random output that appears independent from the source and uniformly distributed.  Examples of weakly random sources include radioactive decay or thermal noise; the only restriction on possible sources is that there is no way they can be fully controlled, calculated or predicted, and that a lower bound on their entropy rate can be established.  For a given source, a randomness extractor can even be considered to be a true random number generator (TRNG); but there is no single extractor that has been proven to produce truly random output from any type of weakly random source.
Sometimes the term "bias" is used to denote a weakly random source's departure from uniformity, and in older literature, some extractors are called unbiasing algorithms, as they take the randomness from a so-called "biased" source and output a distribution that appears unbiased.  The weakly random source will always be longer than the extractor's output, but an efficient extractor is one that lowers this ratio of lengths as much as possible, while simultaneously keeping the seed length low.  Intuitively, this means that as much randomness as possible has been "extracted" from the source.
An extractor has some conceptual similarities with a pseudorandom generator (PRG), but the two concepts are not identical. Both are functions that take as input a small, uniformly random seed and produce a longer output that "looks" uniformly random. Some pseudorandom generators are, in fact, also extractors.  (When a PRG is based on the existence of hard-core predicates, one can think of the weakly random source as a set of truth tables of such predicates and prove that the output is statistically close to uniform.) However, the general PRG definition does not specify that a weakly random source must be used, and while in the case of an extractor, the output should be statistically close to uniform, in a PRG it is only required to be computationally indistinguishable from uniform, a somewhat weaker concept.

## Related

- [[Randomness merger]]
- [[Bach's algorithm]]
- [[Aanderaa–Karp–Rosenberg conjecture]]
- [[Advice (complexity)]]
- [[Analysis of algorithms]]
- [[Approximation algorithm]]
- [[Asymptotic computational complexity]]
- [[Averaging argument]]
- [[B92 protocol]]
- [[BB84]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Randomness_extractor