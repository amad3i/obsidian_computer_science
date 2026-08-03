---
title: "Persistent memory"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Persistent_memory"
wikipedia_categories: ["Computer file systems", "Persistence frameworks"]
related: ["[[Access method]]", "[[Allocate-on-flush]]", "[[Apple File System]]", "[[Apple Partition Map]]", "[[Archive bit]]", "[[Archive file]]", "[[Basic partitioned access method]]", "[[Block allocation map]]", "[[Block availability map]]", "[[Block suballocation]]"]
---

# Persistent memory

In computer science, persistent memory is any method or apparatus for efficiently storing data structures such that they can continue to be accessed using memory instructions or memory APIs even after the end of the process that created or last modified them.
Often confused with non-volatile random-access memory (NVRAM), persistent memory is instead more closely linked to the concept of persistence in its emphasis on program state that exists outside the fault zone of the process that created it. (A process is a program under execution. The fault zone of a process is that subset of program state which could be corrupted by the process continuing to execute after incurring a fault, for instance due to an unreliable component used in the computer executing the program.)
Efficient, memory-like access is the defining characteristic of persistent memory. It can be provided using microprocessor memory instructions, such as load and store. It can also be provided using APIs that implement remote direct memory access (RDMA) actions, such as RDMA read and RDMA write. Other low-latency methods that allow byte-grain access to data also qualify.
Persistent memory capabilities extend beyond non-volatility of stored bits. For instance, the loss of key metadata, such as page table entries or other constructs that translate virtual addresses to physical addresses, may render durable bits non-persistent. In this respect, persistent memory resembles more abstract forms of computer storage, such as file systems. In fact, almost all existing persistent memory technologies implement at least a basic file system that can be used for associating names or identifiers with stored extents, and at a minimum provide file system methods that can be used for naming and allocating such extents.

## Related

- [[Access method]]
- [[Allocate-on-flush]]
- [[Apple File System]]
- [[Apple Partition Map]]
- [[Archive bit]]
- [[Archive file]]
- [[Basic partitioned access method]]
- [[Block allocation map]]
- [[Block availability map]]
- [[Block suballocation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Persistent_memory