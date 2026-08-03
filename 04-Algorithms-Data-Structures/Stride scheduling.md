---
title: "Stride scheduling"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Stride_scheduling"
wikipedia_categories: ["Computational resources", "Computer science stubs", "Concurrency control algorithms", "Concurrent computing", "Processor scheduling algorithms"]
related: ["[[Concurrency pattern]]", "[[Lamport's distributed mutual exclusion algorithm]]", "[[Naimi–Trehel algorithm]]", "[[Protected procedure]]", "[[Relativistic programming]]", "[[Actor model]]", "[[Alewife (multiprocessor)]]", "[[ALF (proof assistant)]]", "[[Analog image processing]]", "[[AQUA@home]]"]
---

# Stride scheduling

Stride scheduling is a type of scheduling mechanism that has been introduced as a simple concept to achieve proportional central processing unit (CPU) capacity reservation among concurrent processes. Stride scheduling aims to sequentially allocate a resource for the duration of standard time-slices (quantum) in a fashion, that performs periodic recurrences of allocations. Thus, a process p1 which has reserved twice the share of a process p2 will be allocated twice as often as p2. In particular, process p1 will even be allocated two times every time p2 is waiting for allocation, assuming that neither of the two processes performs a blocking operation.

## Related

- [[Concurrency pattern]]
- [[Lamport's distributed mutual exclusion algorithm]]
- [[Naimi–Trehel algorithm]]
- [[Protected procedure]]
- [[Relativistic programming]]
- [[Actor model]]
- [[Alewife (multiprocessor)]]
- [[ALF (proof assistant)]]
- [[Analog image processing]]
- [[AQUA@home]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Stride_scheduling