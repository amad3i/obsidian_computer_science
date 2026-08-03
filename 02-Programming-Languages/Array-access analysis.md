---
title: "Array-access analysis"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Array-access_analysis"
wikipedia_categories: ["Compiler construction", "Programming language topic stubs", "Static program analysis"]
related: ["[[Call graph]]", "[[Literal pool]]", "[[Metacompilation]]", "[[Semantic dictionary encoding]]", "[[Trace scheduling]]", "[[A-normal form]]", "[[Abstract syntax]]", "[[Access query language]]", "[[Affix grammar]]", "[[Alef (programming language)]]"]
---

# Array-access analysis

In computer science, array-access analysis is a compiler analysis approach used to decide the read and write access patterns to elements or portions of arrays.
The major data type manipulated in scientific programs is the array. The define/use analysis on a whole array is insufficient for aggressive compiler optimizations such as auto parallelization and array privatization. Array access analysis aims to obtain the knowledge of which portions or even which elements of the array are accessed by a given code segment (basic block, loop, or even at the procedure level). 
Array-access analysis can be largely categorized into exact (or reference-list-based) and summary methods for different tradeoffs of accuracy and complexity. Exact methods are precise but very costly in terms of computation and space storage, while summary methods are approximate but can be computed quickly and economically. 
Typical exact array-access analysis include linearization and atom images. Summary methods can be further divided into array sections, bounded regular sections using triplet notation, linear-constraint methods such as data-access descriptors and array-region analysis.

## Related

- [[Call graph]]
- [[Literal pool]]
- [[Metacompilation]]
- [[Semantic dictionary encoding]]
- [[Trace scheduling]]
- [[A-normal form]]
- [[Abstract syntax]]
- [[Access query language]]
- [[Affix grammar]]
- [[Alef (programming language)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Array-access_analysis