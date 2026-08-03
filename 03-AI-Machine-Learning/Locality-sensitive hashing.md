---
title: "Locality-sensitive hashing"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Locality-sensitive_hashing"
wikipedia_categories: ["Classification algorithms", "Dimension reduction", "Hashing", "Probabilistic data structures", "Search algorithms"]
related: ["[[Nearest neighbor search]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[Cuckoo hashing]]", "[[Double hashing]]", "[[Dynamic perfect hashing]]", "[[Extendible hashing]]", "[[Hopscotch hashing]]", "[[Index mapping]]", "[[K-nearest neighbors algorithm]]", "[[Linear hashing]]"]
---

# Locality-sensitive hashing

In computer science, locality-sensitive hashing (LSH) is a fuzzy hashing technique that hashes similar input items into the same "buckets" with high probability. The number of buckets is much smaller than the universe of possible input items. Since similar items end up in the same buckets, this technique can be used for data clustering and nearest neighbor search. It differs from conventional hashing techniques in that hash collisions are maximized, not minimized. Alternatively, the technique can be seen as a way to reduce the dimensionality of high-dimensional data; high-dimensional input items can be reduced to low-dimensional versions while preserving relative distances between items.
Hashing-based approximate nearest-neighbor search algorithms generally use one of two main categories of hashing methods: either data-independent methods, such as locality-sensitive hashing (LSH); or data-dependent methods, such as locality-preserving hashing (LPH).
Locality-preserving hashing was initially devised as a way to facilitate data pipelining in implementations of massively parallel algorithms that use randomized routing and universal hashing to reduce memory contention and network congestion.

## Related

- [[Nearest neighbor search]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[Cuckoo hashing]]
- [[Double hashing]]
- [[Dynamic perfect hashing]]
- [[Extendible hashing]]
- [[Hopscotch hashing]]
- [[Index mapping]]
- [[K-nearest neighbors algorithm]]
- [[Linear hashing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Locality-sensitive_hashing