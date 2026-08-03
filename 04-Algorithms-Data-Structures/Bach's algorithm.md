---
title: "Bach's algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Bach's_algorithm"
wikipedia_categories: ["Algorithms and data structures stubs", "Cryptographic algorithms", "Random number generation"]
related: ["[[Randomness extractor]]", "[[Randomness merger]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[Almeida–Pineda recurrent backpropagation]]", "[[B92 protocol]]", "[[Badouel intersection algorithm]]", "[[BB84]]", "[[Beaufort cipher]]", "[[Best bin first]]", "[[Block cipher mode of operation]]"]
---

# Bach's algorithm

Bach's algorithm is a probabilistic polynomial time algorithm for generating random numbers along with their factorization. It was published by Eric Bach in 1988. No algorithm is known that efficiently factors random numbers, so the straightforward method, namely generating a random number and then factoring it, is impractical.
The algorithm performs, in expectation, O(log n) primality tests. A simpler but less-efficient algorithm (performing, in expectation, O(log2 n) primality tests), is due to Adam Kalai.
Bach's algorithm may be used as part of certain methods for key generation in cryptography.

## Related

- [[Randomness extractor]]
- [[Randomness merger]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[Almeida–Pineda recurrent backpropagation]]
- [[B92 protocol]]
- [[Badouel intersection algorithm]]
- [[BB84]]
- [[Beaufort cipher]]
- [[Best bin first]]
- [[Block cipher mode of operation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Bach's_algorithm