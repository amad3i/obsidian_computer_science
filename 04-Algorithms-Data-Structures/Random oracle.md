---
title: "Random oracle"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Random_oracle"
wikipedia_categories: ["Computation oracles", "Cryptographic hash functions", "Theory of cryptography"]
related: ["[[HAIFA construction]]", "[[Puzzle friendliness]]", "[[Sponge function]]", "[[Argon2]]", "[[Ascon (cipher)]]", "[[Averaging argument]]", "[[Bcrypt]]", "[[Bent function]]", "[[Collision attack]]", "[[Comparison of cryptographic hash functions]]"]
---

# Random oracle

In cryptography, a random oracle is an oracle (a theoretical black box) that responds to every unique query with a (truly) random response chosen uniformly from its output domain. If a query is repeated, it responds the  same way every time that query is submitted.
Stated differently, a random oracle is a mathematical function chosen uniformly at random, that is, a function mapping each possible query to a (fixed) random response from its output domain.
Random oracles first appeared in the context of complexity theory, in which they were used to argue that complexity class separations may face relativization barriers, with the most prominent case being the P vs NP problem, two classes shown in 1981 to be distinct relative to a random oracle almost surely. They made their way into cryptography by the publication of Mihir Bellare and Phillip Rogaway in 1993, which introduced them as a formal cryptographic model to be used in reduction proofs.
They are typically used when the proof cannot be carried out using weaker assumptions on the cryptographic hash function. A system that is proven secure when every hash function is replaced by a random oracle is described as being secure in the random oracle model, a differentiation from being secure in the standard model of cryptography.

## Related

- [[HAIFA construction]]
- [[Puzzle friendliness]]
- [[Sponge function]]
- [[Argon2]]
- [[Ascon (cipher)]]
- [[Averaging argument]]
- [[Bcrypt]]
- [[Bent function]]
- [[Collision attack]]
- [[Comparison of cryptographic hash functions]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Random_oracle