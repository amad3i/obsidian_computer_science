---
title: "Barrier (computer science)"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Barrier_(computer_science)"
wikipedia_categories: ["Concurrency (computer science)", "Concurrency control", "Parallel computing", "Synchronization"]
related: ["[[Semaphore (programming)]]", "[[Language of Temporal Ordering Specification]]", "[[Advanced Synchronization Facility]]", "[[Speculative multithreading]]", "[[Synchronization (computer science)]]", "[[Transactional Synchronization Extensions]]", "[[ABIT BP6]]", "[[ACID]]", "[[Active object]]", "[[Aiyara cluster]]"]
---

# Barrier (computer science)

In parallel computing, a barrier is a synchronization method. A barrier for a group of threads or processes in the source code means that all thread/process stop at that point and do not proceed until all other threads/processes reach this barrier.
Many collective routines and directive-based parallel languages impose implicit barriers. For example, a parallel do loop in Fortran with OpenMP will not be allowed to continue on any thread until the last iteration is completed. This is in case the program relies on the result of the loop immediately after its completion. In message passing, any global communication (such as reduction or scatter) may imply a barrier.
In concurrent computing, a barrier may be in a "raised" or "lowered state". The term "latch" is sometimes used to refer to a barrier that starts in the raised state and cannot be re-raised once it is in the lowered state. The term "count-down latch" is sometimes used to refer to a latch that is automatically lowered once a predetermined number of threads/processes have arrived.

## Related

- [[Semaphore (programming)]]
- [[Language of Temporal Ordering Specification]]
- [[Advanced Synchronization Facility]]
- [[Speculative multithreading]]
- [[Synchronization (computer science)]]
- [[Transactional Synchronization Extensions]]
- [[ABIT BP6]]
- [[ACID]]
- [[Active object]]
- [[Aiyara cluster]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Barrier_(computer_science)