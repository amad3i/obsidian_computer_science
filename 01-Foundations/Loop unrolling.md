---
title: "Loop unrolling"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Loop_unrolling"
wikipedia_categories: ["Compiler optimizations", "Parallel computing"]
related: ["[[Automatic parallelization]]", "[[Automatic vectorization]]", "[[Flattening transformation]]", "[[ABIT BP6]]", "[[Advanced Synchronization Facility]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Algorithmic skeleton]]", "[[All nearest smaller values]]", "[[All-to-all (parallel pattern)]]"]
---

# Loop unrolling

Loop unrolling, also known as loop unwinding, is a loop transformation technique that attempts to optimize a program's execution speed at the expense of its binary size, which is an approach known as  space–time tradeoff. The transformation can be undertaken manually by the programmer or by an optimizing compiler. On modern processors, loop unrolling is often counterproductive, as the increased code size can cause more cache misses; cf. Duff's device.
The goal of loop unwinding is to increase a program's speed by reducing or eliminating instructions that control the loop, such as pointer arithmetic and "end of loop" tests on each iteration; reducing branch penalties; as well as hiding latencies, including the delay in reading data from memory. To eliminate this computational overhead, loops can be re-written as a repeated sequence of similar independent statements.
Loop unrolling is also part of certain formal verification techniques, in particular bounded model checking.

## Related

- [[Automatic parallelization]]
- [[Automatic vectorization]]
- [[Flattening transformation]]
- [[ABIT BP6]]
- [[Advanced Synchronization Facility]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]
- [[Algorithmic skeleton]]
- [[All nearest smaller values]]
- [[All-to-all (parallel pattern)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Loop_unrolling