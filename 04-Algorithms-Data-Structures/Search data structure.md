---
title: "Search data structure"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Search_data_structure"
wikipedia_categories: ["Data structures"]
related: ["[[Active data structure]]", "[[Block availability map]]", "[[Comparison of data structures]]", "[[Compressed data structure]]", "[[Control block]]", "[[Directed acyclic graph]]", "[[Dynamization]]", "[[Implicit data structure]]", "[[Interval union-split-find]]", "[[List of data structures]]"]
---

# Search data structure

In computer science, a search data structure is any data structure that allows the efficient retrieval of specific items from a set of items, such as a specific record from a database.
The simplest, most general, and least efficient search structure is merely an unordered sequential list of all the items. Locating the desired item in such a list, by the linear search method, inevitably requires a number of operations proportional to the number n of items, in the worst case as well as in the average case.  Useful search data structures allow faster retrieval; however, they are limited to queries of some specific kind.  Moreover, since the cost of building such structures is at least proportional to n, they only pay off if several queries are to be performed on the same database (or on a database that changes little between queries).
Static search structures are designed for answering many queries on a fixed database; dynamic structures also allow insertion, deletion, or modification of items between successive queries. In the dynamic case, one must also consider the cost of fixing the search structure to account for the changes in the database.

## Related

- [[Active data structure]]
- [[Block availability map]]
- [[Comparison of data structures]]
- [[Compressed data structure]]
- [[Control block]]
- [[Directed acyclic graph]]
- [[Dynamization]]
- [[Implicit data structure]]
- [[Interval union-split-find]]
- [[List of data structures]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Search_data_structure