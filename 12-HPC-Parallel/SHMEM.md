---
title: "SHMEM"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/SHMEM"
wikipedia_categories: ["Application programming interfaces", "Parallel computing"]
related: ["[[ISP Formal Verification Tool]]", "[[Message Passing Interface]]", "[[OpenACC]]", "[[OpenCL]]", "[[OpenHMPP]]", "[[OpenMP]]", "[[Portals network programming application programming interface]]", "[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]"]
---

# SHMEM

SHMEM (from Cray Research's “shared memory” library) is a family of parallel programming libraries, providing one-sided, RDMA, parallel-processing interfaces for low-latency distributed-memory supercomputers.  The SHMEM acronym was subsequently reverse engineered to mean "Symmetric Hierarchical MEMory”. Later it was expanded to distributed memory parallel computer clusters, and is used as parallel programming interface or as low-level interface to build partitioned global address space (PGAS) systems and languages. “Libsma”, the first SHMEM library, was created by Richard Smith at Cray Research in 1993 as a set of thin interfaces to access the CRAY T3D's inter-processor-communication hardware.  SHMEM has been implemented by Cray Research, SGI, Cray Inc., Quadrics, HP, GSHMEM, IBM, QLogic, Mellanox, Universities of Houston and Florida, Stony Brook University, and Texas-Tech University; there is also open-source OpenSHMEM.
SHMEM laid the foundations for low-latency (sub-microsecond) one-sided communication. After its use on the CRAY T3E, its popularity waned as few machines could deliver the near-microsecond latencies necessary to maintain efficiency for its hallmark individual-word communication.  With the advent of popular sub-microsecond interconnects, SHMEM has been used to address the necessity of hyper-efficient, portable, parallel-communication methods for exascale computing.
Programs written using SHMEM can be started on several computers, connected together with some high-performance network, supported by used SHMEM library. Every computer runs a copy of a program (SPMD); each copy is called PE (processing element). PEs can ask the SHMEM library to do remote memory-access operations, like reading ("shmem_get" operation) or writing ("shmem_put" operation) data. Peer-to-peer operations are one-sided, which means that no active cooperation from remote thread is needed to complete the action (but it can poll its local memory for changes using "shmem_wait"). Operations can be done on short types like bytes or words, or on longer datatypes like arrays, sometimes evenly strided or indexed (only some elements of array are sent). For short datatypes, SHMEM can do atomic operations (CAS, fetch and add, atomic increment, etc.) even in remote memory. Also there are two different synchronization methods: task control sync (barriers and locks) and functions to enforce memory fencing and ordering. SHMEM has several collective operations, which should be started by all PEs, like reductions, broadcast, collect.
Every PE has some of its memory declared as "symmetric" segments (or shared memory area), and other memory is private. Only "shared" memory can be accessed in one-sided operation from remote PEs.  Programmers can use static-memory constructs or shmem_malloc/shmem_free routines to create objects with symmetric addresses that span the PEs.

## Related

- [[ISP Formal Verification Tool]]
- [[Message Passing Interface]]
- [[OpenACC]]
- [[OpenCL]]
- [[OpenHMPP]]
- [[OpenMP]]
- [[Portals network programming application programming interface]]
- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/SHMEM