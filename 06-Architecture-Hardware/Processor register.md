---
title: "Processor register"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Processor_register"
wikipedia_categories: ["Central processing unit", "Computer architecture", "Digital registers"]
related: ["[[Arithmetic logic unit]]", "[[Byte addressing]]", "[[Computer architecture]]", "[[Control register]]", "[[Flag (programming)]]", "[[Frequency scaling]]", "[[Register file]]", "[[Simultaneous multithreading]]", "[[Temporal multithreading]]", "[[Abstraction layer]]"]
---

# Processor register

A processor register is a quickly accessible storage location available to a computer's processor. Registers usually consist of a small amount of fast storage, although some registers have specific hardware functions, and may be read-only or write-only. In computer architecture, registers are typically addressed by mechanisms other than main memory, but may in some cases be assigned a memory address e.g. the DEC PDP-6/PDP-10 and the ICT 1900.
Almost all computers, whether load/store architecture or not, load items of data from a larger memory into registers where they are used for arithmetic operations, bitwise operations, and other operations, and are manipulated or tested by machine instructions. Manipulated items are then often stored back to main memory, either by the same instruction or by a subsequent one. Modern processors use either static or dynamic random-access memory (RAM) as main memory, with the latter usually accessed via one or more cache levels.
Processor registers are normally at the top of the memory hierarchy, and provide the fastest way to access data. The term normally refers only to the group of registers that are directly encoded as part of an instruction, as defined by the instruction set. However, modern high-performance CPUs often have duplicates of these "architectural registers" in order to improve performance via register renaming, allowing parallel and speculative execution. Modern x86 design acquired these techniques around 1995 with the releases of Pentium Pro, Cyrix 6x86, Nx586, and AMD K5.
When a computer program accesses the same data repeatedly, this is called locality of reference.  Holding frequently used values in registers can be critical to a program's performance. Register allocation is performed either by a compiler in the code generation phase, or manually by an assembly language programmer.

## Related

- [[Arithmetic logic unit]]
- [[Byte addressing]]
- [[Computer architecture]]
- [[Control register]]
- [[Flag (programming)]]
- [[Frequency scaling]]
- [[Register file]]
- [[Simultaneous multithreading]]
- [[Temporal multithreading]]
- [[Abstraction layer]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Processor_register