---
title: "Extendible hashing"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Extendible_hashing"
wikipedia_categories: ["Hashing", "Search algorithms"]
related: ["[[Cuckoo hashing]]", "[[Double hashing]]", "[[Dynamic perfect hashing]]", "[[Hopscotch hashing]]", "[[Index mapping]]", "[[Linear hashing]]", "[[Linear probing]]", "[[Locality-sensitive hashing]]", "[[Perfect hash function]]", "[[Quadratic probing]]"]
---

# Extendible hashing

Extendible hashing is a type of hash system which treats a hash as a bit string and uses a trie for bucket lookup. Because of the hierarchical nature of the system, re-hashing is an incremental operation (done one bucket at a time, as needed).  This means that time-sensitive applications are less affected by table growth than by standard full-table rehashes.
Extendible hashing was described by Ronald Fagin in 1979. Practically all modern filesystems use either extendible hashing or B-trees. In particular, the Global File System, GPFS, ZFS, and the SpadFS filesystem use extendible hashing.

## Related

- [[Cuckoo hashing]]
- [[Double hashing]]
- [[Dynamic perfect hashing]]
- [[Hopscotch hashing]]
- [[Index mapping]]
- [[Linear hashing]]
- [[Linear probing]]
- [[Locality-sensitive hashing]]
- [[Perfect hash function]]
- [[Quadratic probing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Extendible_hashing