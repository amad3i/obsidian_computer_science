---
title: "Data memory-dependent prefetcher"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Data_memory-dependent_prefetcher"
wikipedia_categories: ["Computer architecture", "Computing stubs", "Digital circuits"]
related: ["[[Arithmetic logic unit]]", "[[Slot (computer architecture)]]", "[[Abstraction layer]]", "[[Address space]]", "[[Addressing mode]]", "[[Aperture (computer memory)]]", "[[Approximate computing]]", "[[Auditory display]]", "[[Automatic system recovery]]", "[[Autonomous decentralized system]]"]
---

# Data memory-dependent prefetcher

A data memory-dependent prefetcher (DMP) is a cache prefetcher that looks at cache memory content for possible pointer values, and prefetches the data at those locations into cache if it sees memory access patterns that suggest following those pointers would be useful.
As of 2022, data prefetching was already a common feature in CPUs, but most prefetchers do not inspect the data within the cache for pointers, instead working by monitoring memory access patterns. Data memory-dependent prefetchers take this one step further.
The DMP in Apple's M1 computer architecture was demonstrated to be capable of being used as a memory side-channel in an attack published in early 2024. At that time its authors did not know of any practical way to exploit it. The DMP was subsequently discovered to be even more opportunistic than previously thought, and has now been demonstrated to be able to be used to effectively attack a variety of cryptographic algorithms in work called GoFetch by its authors.
Intel Core processors also have DMP functionality (Intel use the term "Data Dependent Prefetcher") but Intel states that they have features to prevent their DMPs being used for side-channel attacks. The authors of GoFetch state that they were unable to make their exploit work on Intel processors.

## Related

- [[Arithmetic logic unit]]
- [[Slot (computer architecture)]]
- [[Abstraction layer]]
- [[Address space]]
- [[Addressing mode]]
- [[Aperture (computer memory)]]
- [[Approximate computing]]
- [[Auditory display]]
- [[Automatic system recovery]]
- [[Autonomous decentralized system]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Data_memory-dependent_prefetcher