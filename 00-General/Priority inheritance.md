---
title: "Priority inheritance"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Priority_inheritance"
wikipedia_categories: ["Computer science stubs", "Concurrency control", "Real-time computing"]
related: ["[[Priority ceiling protocol]]", "[[ACID]]", "[[Advanced Synchronization Facility]]", "[[Alewife (multiprocessor)]]", "[[ALF (proof assistant)]]", "[[Analog image processing]]", "[[AQUA@home]]", "[[AQuoSA]]", "[[Arthur Pollen]]", "[[Asynchrony (computer programming)]]"]
---

# Priority inheritance

In real-time computing, priority inheritance is a method for eliminating unbounded priority inversion. Using this programming method, a process scheduling algorithm increases the priority of a process (A) to the maximum priority of any other process waiting for any resource on which A has a resource lock (if it is higher than the original priority of A).
The basic idea of the priority inheritance protocol is that when a job blocks one or more high-priority jobs, it ignores its original priority assignment and executes its critical section at an elevated priority level. After executing its critical section and releasing its locks, the process returns to its original priority level.

## Related

- [[Priority ceiling protocol]]
- [[ACID]]
- [[Advanced Synchronization Facility]]
- [[Alewife (multiprocessor)]]
- [[ALF (proof assistant)]]
- [[Analog image processing]]
- [[AQUA@home]]
- [[AQuoSA]]
- [[Arthur Pollen]]
- [[Asynchrony (computer programming)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Priority_inheritance