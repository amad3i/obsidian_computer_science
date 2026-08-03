---
title: "Multiple instruction, single data"
tags: ["cs", "hpc-parallel", "intermediate"]
domain: HPC & Parallel
level: intermediate
source: "https://en.wikipedia.org/wiki/Multiple_instruction,_single_data"
wikipedia_categories: ["Classes of computers", "Flynn's taxonomy", "Parallel computing"]
related: ["[[Asymmetric multiprocessing]]", "[[Multiple instruction, multiple data]]", "[[Single instruction, multiple data]]", "[[Symmetric multiprocessing]]", "[[Amorphous computing]]", "[[Cellular architecture]]", "[[Computer cluster]]", "[[Fifth Generation Computer Systems]]", "[[Flynn's taxonomy]]", "[[Locale (computer hardware)]]"]
---

# Multiple instruction, single data

In computing, multiple instruction, single data (MISD) is a type of parallel computing architecture where many functional units perform different operations on the same data. Pipeline architectures belong to this type, although they arguably differ in that the data is different after processing by each stage in the pipeline. Fault tolerance executing the same instructions redundantly in order to detect and mask errors, in a manner known as task replication, may be considered to belong to this type. Applications for this architecture are much less common than MIMD and SIMD, as the latter two are often more appropriate for common data parallel techniques.  Specifically, they allow better scaling and use of computational resources.  However, one prominent example of MISD in computing are the Space Shuttle flight control computers.

## Related

- [[Asymmetric multiprocessing]]
- [[Multiple instruction, multiple data]]
- [[Single instruction, multiple data]]
- [[Symmetric multiprocessing]]
- [[Amorphous computing]]
- [[Cellular architecture]]
- [[Computer cluster]]
- [[Fifth Generation Computer Systems]]
- [[Flynn's taxonomy]]
- [[Locale (computer hardware)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Multiple_instruction,_single_data