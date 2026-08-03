---
title: "Persistent data structure"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Persistent_data_structure"
wikipedia_categories: ["Data structures", "Persistence"]
related: ["[[Active data structure]]", "[[Block availability map]]", "[[Comparison of data structures]]", "[[Compressed data structure]]", "[[Control block]]", "[[Core Data]]", "[[Directed acyclic graph]]", "[[Dynamization]]", "[[Implicit data structure]]", "[[Interval union-split-find]]"]
---

# Persistent data structure

In computing, a persistent data structure or not ephemeral data structure is a data structure that always preserves the previous version of itself when it is modified. Such data structures are effectively immutable, as their operations do not (visibly) update the structure in-place, but instead always yield a new updated structure. The term was introduced in Driscoll, Sarnak, Sleator, and Tarjan's 1986 article.
A data structure is partially persistent if all versions can be accessed but only the newest version can be modified. The data structure is fully persistent if every version can be both accessed and modified. If there is also a meld or merge operation that can create a new version from two previous versions, the data structure is called confluently persistent. Structures that are not persistent are called ephemeral.
These types of data structures are particularly common in logical and functional programming, as languages in those paradigms discourage (or fully forbid) the use of mutable data.

## Related

- [[Active data structure]]
- [[Block availability map]]
- [[Comparison of data structures]]
- [[Compressed data structure]]
- [[Control block]]
- [[Core Data]]
- [[Directed acyclic graph]]
- [[Dynamization]]
- [[Implicit data structure]]
- [[Interval union-split-find]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Persistent_data_structure