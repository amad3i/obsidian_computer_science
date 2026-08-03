---
title: "Dynamic Markov compression"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Dynamic_Markov_compression"
wikipedia_categories: ["Data compression", "Lossless compression algorithms", "Markov models"]
related: ["[[Canonical Huffman code]]", "[[Prefix code]]", "[[Recursive indexing]]", "[[Baum–Welch algorithm]]", "[[Bernoulli scheme]]", "[[BGZF]]", "[[BREACH]]", "[[Burst error]]", "[[CLAWS (linguistics)]]", "[[Codec]]"]
---

# Dynamic Markov compression

Dynamic Markov compression (DMC) is a lossless data compression algorithm developed by Gordon Cormack and Nigel Horspool.  It uses predictive arithmetic coding similar to prediction by partial matching (PPM), except that the input is predicted one bit at a time (rather than one byte at a time).  DMC has a good compression ratio and moderate speed, similar to PPM, but requires somewhat more memory and is not widely implemented.  Some recent implementations include the experimental compression programs hook by Nania Francesco Antonio, ocamyd by Frank Schwellinger, and as a submodel in paq8l by Matt Mahoney.  These are based on the 1993 implementation in C by Gordon Cormack.

## Related

- [[Canonical Huffman code]]
- [[Prefix code]]
- [[Recursive indexing]]
- [[Baum–Welch algorithm]]
- [[Bernoulli scheme]]
- [[BGZF]]
- [[BREACH]]
- [[Burst error]]
- [[CLAWS (linguistics)]]
- [[Codec]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dynamic_Markov_compression