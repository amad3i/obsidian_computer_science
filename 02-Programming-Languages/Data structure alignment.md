---
title: "Data structure alignment"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Data_structure_alignment"
wikipedia_categories: ["Compiler construction", "Composite data types"]
related: ["[[Abstract syntax]]", "[[Affix grammar]]", "[[Algebraic data type]]", "[[Aliasing (computing)]]", "[[Array-access analysis]]", "[[Aspect weaver]]", "[[Associative array]]", "[[Attribute grammar]]", "[[Backus–Naur form]]", "[[Basic block]]"]
---

# Data structure alignment

Data structure alignment is the way data is arranged and accessed in computer memory. It consists of three separate but related issues: data alignment, data structure padding, and packing.
The CPU in modern computer hardware performs reads and writes to memory most efficiently when the data is naturally aligned, which generally means that the data's memory address is a multiple of the data size. For instance, in a 32-bit architecture, the data may be aligned if the data is stored in four consecutive bytes and the first byte lies on a 4-byte boundary.
Data alignment is the aligning of elements according to their natural alignment. To ensure natural alignment, it may be necessary to insert some padding between structure elements or after the last element of a structure. For example, on a 32-bit machine, a data structure containing a 16-bit value followed by a 32-bit value could have 16 bits of padding between the 16-bit value and the 32-bit value to align the 32-bit value on a 32-bit boundary. Alternatively, one can pack the structure, omitting the padding, which may lead to slower access, but saves 16 bits of memory.
Although data structure alignment is a fundamental issue for all modern computers, many programming languages and programming language implementations handle data alignment automatically. Fortran, Ada, PL/I, Pascal, certain C and C++ implementations, D, Rust, C#, and assembly language allow at least partial control of data structure padding, which may be useful in certain special circumstances.

## Related

- [[Abstract syntax]]
- [[Affix grammar]]
- [[Algebraic data type]]
- [[Aliasing (computing)]]
- [[Array-access analysis]]
- [[Aspect weaver]]
- [[Associative array]]
- [[Attribute grammar]]
- [[Backus–Naur form]]
- [[Basic block]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Data_structure_alignment