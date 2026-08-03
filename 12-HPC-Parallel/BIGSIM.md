---
title: "BIGSIM"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/BIGSIM"
wikipedia_categories: ["Parallel computing"]
related: ["[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]", "[[AMD Instinct]]", "[[Amorphous computing]]", "[[Apache Samza]]"]
---

# BIGSIM

BIGSIM is a computer simulation and performance modeling system for parallel computing, typically used for very large computer clusters. BIGSIM was developed at the University of Illinois.
When a large scale, often supercomputer level, parallel system is being developed, it is essential to be able to experiment with multiple configurations and simulate performance. BIGSIM provides these facilities by allowing the simulation of performance on various node topologies, message passing and scheduling strategies. 
BIGSIM includes an emulator and a trace-based simulator. The emulator executes applications on a small number of nodes and stores the results, so the simulator can use them  and simulate activities on a much larger number of nodes. 
The simulator is a discrete event simulator (based on the POSE system) which is trace driven and uses POSE's Charm++ base. BIGSIM can simulate both the processing components and the message passing system to provide an overall view of system performance characteristics. 
The emulator stores information of sequential execution blocks (SEBs) for multiple processors in log files, with each SEB recording the messages sent, their sources and destinations, dependencies, timings, etc. The simulator reads the log files and simulates them, and may star additional messages which are then also stored as SEBs. 
The simulator can thus provide a view of the performance of very large applications, based on the execution traces provided by the emulator on a much smaller number of nodes, before the entire machine is available, or configured.

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

- Wikipedia: https://en.wikipedia.org/wiki/BIGSIM