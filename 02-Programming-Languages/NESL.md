---
title: "NESL"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/NESL"
wikipedia_categories: ["Array programming languages", "Common Lisp (programming language) software", "Concurrent programming languages", "Functional languages", "Programming language topic stubs"]
related: ["[[-Lisp]]", "[[JoCaml]]", "[[SequenceL]]", "[[X10 (programming language)]]", "[[Actor-Based Concurrent Language]]", "[[Alef (programming language)]]", "[[APL (programming language)]]", "[[Chapel (programming language)]]", "[[CMS Pipelines]]", "[[Concurrent ML]]"]
---

# NESL

NESL is a parallel programming language developed at Carnegie Mellon by the SCandAL project and released in 1993. It integrates various ideas from parallel algorithms, functional programming, and array programming languages.
The most important new ideas behind NESL are

Nested data parallelism: this feature offers the benefits of data parallelism, concise code that is easy to understand and debug, while being well suited for irregular algorithms, such as algorithms on trees, graphs or sparse matrices.
A language based performance model: this gives a formal way to calculate the work and depth of a program. These measures can be related to running time on parallel machines.
The main design guideline for NESL was to make parallel programming easy and portable. Algorithms are typically significantly more concise in NESL than in most other parallel programming languages, and the code closely resembles high-level pseudocode.
NESL handles nested data parallelism by using the flattening transformation to convert nested data parallelism to flat data parallelism. This works by storing nested vectors as the nested data and a segment descriptor of vector lengths, separately.
This flattening transform, however, can increase the asymptotic work and space complexity of the original program, leading to a much less efficient result.

## Related

- [[-Lisp]]
- [[JoCaml]]
- [[SequenceL]]
- [[X10 (programming language)]]
- [[Actor-Based Concurrent Language]]
- [[Alef (programming language)]]
- [[APL (programming language)]]
- [[Chapel (programming language)]]
- [[CMS Pipelines]]
- [[Concurrent ML]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/NESL