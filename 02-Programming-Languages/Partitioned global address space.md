---
title: "Partitioned global address space"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Partitioned_global_address_space"
wikipedia_categories: ["Parallel computing", "Programming paradigms"]
related: ["[[Concurrent logic programming]]", "[[Flow-based programming]]", "[[Parallel programming model]]", "[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]"]
---

# Partitioned global address space

In computer science, partitioned global address space (PGAS) is a parallel programming model paradigm. PGAS is typified by communication operations involving a global memory address space abstraction that is logically partitioned, where a portion is local to each process, thread, or processing element. The novelty of PGAS is that the portions of the shared memory space may have an affinity for a particular process, thereby exploiting locality of reference in order to improve performance. A PGAS memory model is featured in various parallel programming languages and libraries, including: Coarray Fortran, Unified Parallel C, Split-C, Fortress, Chapel, X10, UPC++, Coarray C++, Global Arrays, DASH and SHMEM. The PGAS paradigm is now an integrated part of the Fortran language, as of Fortran 2008 which standardized coarrays.
The various languages and libraries offering a PGAS memory model differ widely in other details, such as the base programming language and the mechanisms used to express parallelism. Many PGAS systems combine the advantages of a SPMD programming style for distributed memory systems (as employed by MPI) with the data referencing semantics of shared memory systems. In contrast to message passing, PGAS programming models frequently offer one-sided communication operations such as Remote Memory Access (RMA), whereby one processing element may directly access memory with affinity to a different (potentially remote) process, without explicit semantic involvement by the passive target process. PGAS offers more efficiency and scalability than traditional shared-memory approaches with a flat address space, because hardware-specific data locality can be explicitly exposed in the semantic partitioning of the address space.
A variant of the PGAS paradigm, asynchronous partitioned global address space (APGAS) augments the programming model with facilities for both local and remote asynchronous task creation.  Two programming languages that use this model are Chapel and X10.

## Related

- [[Concurrent logic programming]]
- [[Flow-based programming]]
- [[Parallel programming model]]
- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]
- [[Algorithmic skeleton]]
- [[All nearest smaller values]]
- [[All-to-all (parallel pattern)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Partitioned_global_address_space