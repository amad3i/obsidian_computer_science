---
title: "Perfect hash function"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Perfect_hash_function"
wikipedia_categories: ["Hash functions", "Hashing", "Search algorithms"]
related: ["[[Cuckoo hashing]]", "[[Double hashing]]", "[[Dynamic perfect hashing]]", "[[Extendible hashing]]", "[[Hash function]]", "[[Hopscotch hashing]]", "[[Index mapping]]", "[[K-independent hashing]]", "[[Linear hashing]]", "[[Linear probing]]"]
---

# Perfect hash function

In computer science, a perfect hash function h for a set S is a hash function that maps distinct elements in S to a set of m integers, with no collisions. In mathematical terms, it is an injective function.
Perfect hash functions may be used to implement a lookup table with constant worst-case access time. A perfect hash function can, as any hash function, be used to implement hash tables, with the advantage that no collision resolution has to be implemented. In addition, if the keys are not in the data and if it is known that queried keys will be valid, then the keys do not need to be stored in the lookup table, saving space.
Disadvantages of perfect hash functions are that S needs to be known for the construction of the perfect hash function. Non-dynamic perfect hash functions need to be re-constructed if S changes. For frequently changing S dynamic perfect hash functions may be used at the cost of additional space. The space requirement to store the perfect hash function is in O(n) where n is the number of keys in the structure.
The important performance parameters for perfect hash functions are the evaluation time, which should be constant, the construction time, and the representation size.

## Related

- [[Cuckoo hashing]]
- [[Double hashing]]
- [[Dynamic perfect hashing]]
- [[Extendible hashing]]
- [[Hash function]]
- [[Hopscotch hashing]]
- [[Index mapping]]
- [[K-independent hashing]]
- [[Linear hashing]]
- [[Linear probing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Perfect_hash_function