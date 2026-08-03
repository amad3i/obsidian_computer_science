---
title: "Privatization (computer programming)"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Privatization_(computer_programming)"
wikipedia_categories: ["Computer programming"]
related: ["[[Algorave]]", "[[Asynchronous procedure call]]", "[[Asynchrony (computer programming)]]", "[[Bayesian program synthesis]]", "[[Boolean flag]]", "[[Breakpoint]]", "[[Cheat sheet]]", "[[Code Club]]", "[[Code Words]]", "[[Codecademy]]"]
---

# Privatization (computer programming)

Privatization is a technique used in shared-memory programming to enable parallelism, by removing dependencies that occur across different threads in a parallel program. Dependencies between threads arise from two or more threads reading or writing a variable at the same time. Privatization gives each thread a private copy, so it can read and write it independently and thus, simultaneously.
Each parallel algorithm specifies whether a variable is shared or private. Many errors in implementation can arise if the variable is declared to be shared but the algorithm requires it to be private, or vice versa.
Traditionally, parallelizing compilers could apply privatization to scalar elements only. 
To exploit parallelism that occurs across iterations within a parallel program (loop-level parallelism), the need grew for compilers that can also perform array variable privatization. Most of today's compilers can performing array privatization with more features and functions to enhance the performance of the parallel program in general. An example is the Polaris parallelizing compiler.

## Related

- [[Algorave]]
- [[Asynchronous procedure call]]
- [[Asynchrony (computer programming)]]
- [[Bayesian program synthesis]]
- [[Boolean flag]]
- [[Breakpoint]]
- [[Cheat sheet]]
- [[Code Club]]
- [[Code Words]]
- [[Codecademy]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Privatization_(computer_programming)