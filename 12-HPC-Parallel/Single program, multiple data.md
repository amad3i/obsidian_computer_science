---
title: "Single program, multiple data"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Single_program,_multiple_data"
wikipedia_categories: ["Flynn's taxonomy", "Parallel computing"]
related: ["[[Asymmetric multiprocessing]]", "[[Multi-core processor]]", "[[Multiple instruction, multiple data]]", "[[Multiple instruction, single data]]", "[[Single instruction, multiple data]]", "[[Symmetric multiprocessing]]", "[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]"]
---

# Single program, multiple data

In computing, single program, multiple data (SPMD)  is a term that has been used to refer to computational models for exploiting parallelism whereby multiple processors cooperate in the execution of a program in order to obtain results faster.
The term SPMD was introduced in 1983 and was used to denote two different computational models:

by Michel Auguin (University of Nice Sophia-Antipolis) and François Larbey (Thomson/Sintra), as a "fork-and-join" and data-parallel approach where the parallel tasks ("single program") are split-up and run simultaneously in lockstep on multiple SIMD processors with different inputs, and
by Frederica Darema (IBM), where "all (processors) processes  begin executing the same program... but through synchronization directives ... self-schedule themselves to execute different instructions and act on different data"  and enabling MIMD parallelization of a given program, and is a more general approach than data-parallel and more efficient than the fork-and-join for parallel execution on general purpose multiprocessors.
The (IBM) SPMD is the most common style of parallel programming and can be considered a subcategory of MIMD in that it refers to MIMD execution of a given ("single") program. It is also a prerequisite for research concepts such as active messages and distributed shared memory.

## Related

- [[Asymmetric multiprocessing]]
- [[Multi-core processor]]
- [[Multiple instruction, multiple data]]
- [[Multiple instruction, single data]]
- [[Single instruction, multiple data]]
- [[Symmetric multiprocessing]]
- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Single_program,_multiple_data