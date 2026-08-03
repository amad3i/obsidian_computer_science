---
title: "Concurrent hash table"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Concurrent_hash_table"
wikipedia_categories: ["Concurrent computing", "Hash-based data structures"]
related: ["[[Actor model]]", "[[Cache coherence]]", "[[Choreographic programming]]", "[[Communicating sequential processes]]", "[[Computer cluster]]", "[[Computer multitasking]]", "[[Concurrency pattern]]", "[[Concurrent computing]]", "[[Concurrent constraint logic programming]]", "[[Concurrent object-oriented programming]]"]
---

# Concurrent hash table

A concurrent hash table or concurrent hash map is an implementation of hash tables allowing concurrent access by multiple threads using a hash function.
Concurrent hash tables represent a key concurrent data structure for use in concurrent computing which allow multiple threads to more efficiently cooperate for a computation among shared data.
Due to the natural problems associated with concurrent access - namely contention - the way and scope in which the table can be concurrently accessed differs depending on the implementation. Furthermore, the resulting speed up might not be linear with the amount of threads used as contention needs to be resolved, producing processing overhead. There exist multiple solutions to mitigate the effects of contention, that each preserve the correctness of operations on the table.
As with their sequential counterpart, concurrent hash tables can be generalized and extended to fit broader applications, such as allowing more complex data types to be used for keys and values. These generalizations can however negatively impact performance and should thus be chosen in accordance to the requirements of the application.

## Related

- [[Actor model]]
- [[Cache coherence]]
- [[Choreographic programming]]
- [[Communicating sequential processes]]
- [[Computer cluster]]
- [[Computer multitasking]]
- [[Concurrency pattern]]
- [[Concurrent computing]]
- [[Concurrent constraint logic programming]]
- [[Concurrent object-oriented programming]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Concurrent_hash_table