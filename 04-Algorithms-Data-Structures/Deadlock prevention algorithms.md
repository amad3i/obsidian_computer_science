---
title: "Deadlock prevention algorithms"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Deadlock_prevention_algorithms"
wikipedia_categories: ["Distributed computing"]
related: ["[[ActivityPub]]", "[[AT Protocol]]", "[[Availability zone]]", "[[Botnet]]", "[[CAP theorem]]", "[[CockroachDB]]", "[[Collective operation]]", "[[Comparison of synchronous and asynchronous signalling]]", "[[Confidential Consortium Framework]]", "[[Consensus dynamics]]"]
---

# Deadlock prevention algorithms

In computer science, deadlock prevention algorithms are used in concurrent programming when multiple processes must acquire more than one shared resource.  If two or more concurrent processes obtain multiple resources indiscriminately, a situation can occur where each process has a resource needed by another process.  As a result, none of the processes can obtain all the resources it needs, so all processes are blocked from further execution.  This situation is called a deadlock.  A deadlock prevention algorithm organizes resource usage by each process to ensure that at least one process is always able to get all the resources it needs. One such example of deadlock algorithm is Banker's algorithm.

## Related

- [[ActivityPub]]
- [[AT Protocol]]
- [[Availability zone]]
- [[Botnet]]
- [[CAP theorem]]
- [[CockroachDB]]
- [[Collective operation]]
- [[Comparison of synchronous and asynchronous signalling]]
- [[Confidential Consortium Framework]]
- [[Consensus dynamics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Deadlock_prevention_algorithms