---
title: "Work stealing"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Work_stealing"
wikipedia_categories: ["Parallel computing", "Processor scheduling algorithms"]
related: ["[[Coscheduling]]", "[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]", "[[AMD Instinct]]", "[[Amorphous computing]]"]
---

# Work stealing

In parallel computing, work stealing is a scheduling strategy for multithreaded computer programs. It solves the problem of executing a dynamically multithreaded computation, one that can "spawn" new threads of execution, on a statically multithreaded computer, with a fixed number of processors (or cores). It does so efficiently in terms of execution time, memory usage, and inter-processor communication.
In a work stealing scheduler, each processor in a computer system has a queue of work items (computational tasks, threads) to perform. Each work item consists of a series of instructions, to be executed sequentially, but in the course of its execution, a work item may also spawn new work items that can feasibly be executed in parallel with its other work. These new items are initially put on the queue of the processor executing the work item. When a processor runs out of work, it looks at the queues of the other processors and "steals" their work items. In effect, work stealing distributes the scheduling work over idle processors, and as long as all processors have work to do, no scheduling overhead occurs.
Work stealing contrasts with work sharing, another popular scheduling approach for dynamic multithreading, where each work item is scheduled onto a processor when it is spawned. Compared to this approach, work stealing reduces the amount of process migration between processors, because no such migration occurs when all processors have work to do.
The idea of work stealing goes back to the implementation of the Multilisp programming language and work on parallel functional programming languages in the 1980s. It is employed in the scheduler for the Cilk programming language, the Java fork/join framework, the .NET Task Parallel Library, and the Rust Tokio runtime.

## Related

- [[Coscheduling]]
- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]
- [[Algorithmic skeleton]]
- [[All nearest smaller values]]
- [[All-to-all (parallel pattern)]]
- [[AMD Instinct]]
- [[Amorphous computing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Work_stealing