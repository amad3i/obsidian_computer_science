---
title: "Naimi–Trehel algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Naimi–Trehel_algorithm"
wikipedia_categories: ["Computer science stubs", "Concurrency control algorithms", "Distributed computing"]
related: ["[[Lamport's distributed mutual exclusion algorithm]]", "[[Stride scheduling]]", "[[ActivityPub]]", "[[Alewife (multiprocessor)]]", "[[ALF (proof assistant)]]", "[[Analog image processing]]", "[[AQUA@home]]", "[[Asynchrony (computer programming)]]", "[[AT Protocol]]", "[[Attentive user interface]]"]
---

# Naimi–Trehel algorithm

The Naimi–Trehel algorithm is an algorithm for achieving mutual exclusion in a distributed system.
Unlike Lamport's distributed mutual exclusion algorithm and its related version, this algorithm does not use logical clocks.
This method requires only O(log(number of processes in the network)) messages on average.
When a process invokes a critical section, it sends a request to a queue at a particular processor which is specified by a path built by the algorithm as it runs.

## Related

- [[Lamport's distributed mutual exclusion algorithm]]
- [[Stride scheduling]]
- [[ActivityPub]]
- [[Alewife (multiprocessor)]]
- [[ALF (proof assistant)]]
- [[Analog image processing]]
- [[AQUA@home]]
- [[Asynchrony (computer programming)]]
- [[AT Protocol]]
- [[Attentive user interface]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Naimi–Trehel_algorithm