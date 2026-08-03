---
title: "Protected procedure"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Protected_procedure"
wikipedia_categories: ["Computer science stubs", "Concurrent computing", "Subroutines"]
related: ["[[Concurrency pattern]]", "[[Coroutine]]", "[[First-class message]]", "[[Relativistic programming]]", "[[Stride scheduling]]", "[[Actor model]]", "[[Alewife (multiprocessor)]]", "[[ALF (proof assistant)]]", "[[Analog image processing]]", "[[Anonymous function]]"]
---

# Protected procedure

In computer science, the concept of protected procedure, first introduced as protected service routine in 1965, is necessary when two computations A and B use the same routine S; a protected procedure is such if makes not possible for a malfunction of one of the two computation to cause incorrect execution to the other.
One of the most important aspects of Dennis and Van Horn (hypothetical) system "supervisor" was the inclusion of a description of protected procedure.
In a global environment system (where there's some shared variable), the protected procedure mechanism allows the enforcement of the principle of least privilege and the avoidance of side effects in resources management (see Denning principles).

## Related

- [[Concurrency pattern]]
- [[Coroutine]]
- [[First-class message]]
- [[Relativistic programming]]
- [[Stride scheduling]]
- [[Actor model]]
- [[Alewife (multiprocessor)]]
- [[ALF (proof assistant)]]
- [[Analog image processing]]
- [[Anonymous function]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Protected_procedure