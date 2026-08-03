---
title: "Software fault tolerance"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Software_fault_tolerance"
wikipedia_categories: ["Fault tolerance", "Software architecture", "Software quality"]
related: ["[[Fault tolerance]]", "[[SQALE]]", "[[4+1 architectural view model]]", "[[Active reviews for intermediate designs]]", "[[Agent architecture]]", "[[Amplitude-shift keying]]", "[[Anemic domain model]]", "[[Application domain]]", "[[Application server]]", "[[ArchiMate]]"]
---

# Software fault tolerance

Software fault tolerance is the ability of computer software to continue its normal operation despite the presence of system or hardware faults. Fault-tolerant software has the ability to satisfy requirements despite failures.
Following design patterns should be combined to make the system more fault tolerant: retry, fallback, timeout, circuit breaker, and bulkhead pattern.
To make your system more fault tolerant, you should measure 99th percentile latency and keep the remaining 1% (a.k.a. tail latencies) in check through self healing mechanisms.

## Related

- [[Fault tolerance]]
- [[SQALE]]
- [[4+1 architectural view model]]
- [[Active reviews for intermediate designs]]
- [[Agent architecture]]
- [[Amplitude-shift keying]]
- [[Anemic domain model]]
- [[Application domain]]
- [[Application server]]
- [[ArchiMate]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Software_fault_tolerance