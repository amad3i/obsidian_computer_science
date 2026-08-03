---
title: "LAM/MPI"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/LAM/MPI"
wikipedia_categories: ["Parallel computing"]
related: ["[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]", "[[AMD Instinct]]", "[[Amorphous computing]]", "[[Apache Samza]]"]
---

# LAM/MPI

LAM/MPI is one of the predecessors of the Open MPI project.  Open MPI represents a community-driven, next generation implementation of a Message Passing Interface (MPI) fundamentally designed upon a component architecture to make an extremely powerful platform for high-performance computing. LAM/MPI was officially retired in March 2015.
LAM (Local Area Multicomputer) is an MPI programming environment and development system for heterogeneous computers on a network. With LAM/MPI, a dedicated computer cluster or an existing network computing infrastructure can act as a single parallel computing resource.  LAM/MPI is considered to be "cluster friendly", in that it offers daemon-based process startup/control as well as fast client-to-client message passing protocols.  LAM/MPI can use TCP/IP, shared memory, Myrinet (GM), or Infiniband (mVAPI) for message passing.
LAM features a full implementation of MPI-1 and much of MPI-2.  Compliant applications are source code portable between LAM/MPI and any other implementation of MPI.  In addition to providing a high-quality implementation of the MPI standard, LAM/MPI offers extensive monitoring capabilities to support debugging.  Monitoring happens on two levels.  First, LAM/MPI has the hooks to allow a snapshot of process and message status to be taken at any time during an application run.  This snapshot includes all aspects of synchronization plus datatype maps/signatures, communicator group membership, and message contents (see the XMPI application on the main LAM web site).  On the second level, the MPI library is instrumented to produce a cumulative record of communication, which can be visualized either at runtime or post-mortem.

## Related

- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]
- [[Algorithmic skeleton]]
- [[All nearest smaller values]]
- [[All-to-all (parallel pattern)]]
- [[AMD Instinct]]
- [[Amorphous computing]]
- [[Apache Samza]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/LAM/MPI