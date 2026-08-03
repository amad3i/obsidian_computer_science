---
title: "Linear hashing"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Linear_hashing"
wikipedia_categories: ["Hashing", "Search algorithms"]
related: ["[[Cuckoo hashing]]", "[[Double hashing]]", "[[Dynamic perfect hashing]]", "[[Extendible hashing]]", "[[Hopscotch hashing]]", "[[Index mapping]]", "[[Linear probing]]", "[[Locality-sensitive hashing]]", "[[Perfect hash function]]", "[[Quadratic probing]]"]
---

# Linear hashing

Linear hashing (LH) is a dynamic data structure which implements a hash table and grows or shrinks one bucket at a time. It was invented by Witold Litwin in 1980.
  It has been analyzed by Baeza-Yates and Soza-Pollman. It is the first in a number of schemes known as dynamic hashing
 such as Larson's Linear Hashing with Partial Extensions, Linear Hashing with Priority Splitting, Linear Hashing with Partial Expansions and Priority Splitting, or Recursive Linear Hashing.
The file structure of a dynamic hashing data structure adapts itself to changes in the size of the file, so expensive periodic file reorganization is avoided. A Linear Hashing file expands by splitting a predetermined bucket into two and shrinks by merging two predetermined buckets into one. The trigger for a reconstruction depends on the flavor of the scheme; it could be an overflow at a bucket or load factor (i.e., the number of records divided by the number of buckets) moving outside of a predetermined range. In Linear Hashing there are two types of buckets, those that are to be split and those already split. While extendible hashing splits only overflowing buckets, spiral hashing (a.k.a. spiral storage) distributes records unevenly over the buckets such that buckets with high costs of insertion, deletion, or retrieval are earliest in line for a split.
Linear Hashing has also been made into a scalable distributed data structure, LH*. In LH*, each bucket resides at a different server. LH* itself has been expanded to provide data availability in the presence of failed buckets. Key based operations (inserts, deletes, updates, reads) in LH and LH* take maximum constant time independent of the number of buckets and hence of records.

## Related

- [[Cuckoo hashing]]
- [[Double hashing]]
- [[Dynamic perfect hashing]]
- [[Extendible hashing]]
- [[Hopscotch hashing]]
- [[Index mapping]]
- [[Linear probing]]
- [[Locality-sensitive hashing]]
- [[Perfect hash function]]
- [[Quadratic probing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Linear_hashing