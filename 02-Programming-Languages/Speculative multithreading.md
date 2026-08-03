---
title: "Speculative multithreading"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Speculative_multithreading"
wikipedia_categories: ["Concurrency control", "Instruction processing", "Parallel computing", "Programming language implementation"]
related: ["[[Advanced Synchronization Facility]]", "[[Barrier (computer science)]]", "[[Degree of parallelism]]", "[[General-purpose computing on graphics processing units]]", "[[Instruction-level parallelism]]", "[[Memory-level parallelism]]", "[[Multithreading (computer architecture)]]", "[[Semaphore (programming)]]", "[[Transactional Synchronization Extensions]]", "[[Very long instruction word]]"]
---

# Speculative multithreading

Thread Level Speculation (TLS), also known as Speculative Multi-threading, or Speculative Parallelization, is a technique to speculatively execute a section of computer code that is anticipated to be executed later in parallel with the normal execution on a separate independent thread.  Such a speculative thread may need to make assumptions about the values of input variables. If these prove to be invalid, then the portions of the speculative thread that rely on these input variables will need to be discarded and squashed.  If the assumptions are correct the program can complete in a shorter time provided the thread was able to be scheduled efficiently.

## Related

- [[Advanced Synchronization Facility]]
- [[Barrier (computer science)]]
- [[Degree of parallelism]]
- [[General-purpose computing on graphics processing units]]
- [[Instruction-level parallelism]]
- [[Memory-level parallelism]]
- [[Multithreading (computer architecture)]]
- [[Semaphore (programming)]]
- [[Transactional Synchronization Extensions]]
- [[Very long instruction word]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Speculative_multithreading