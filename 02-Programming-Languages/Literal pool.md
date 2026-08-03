---
title: "Literal pool"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Literal_pool"
wikipedia_categories: ["Compiler construction", "Programming language topic stubs"]
related: ["[[Array-access analysis]]", "[[Metacompilation]]", "[[Semantic dictionary encoding]]", "[[Trace scheduling]]", "[[A-normal form]]", "[[Abstract syntax]]", "[[Access query language]]", "[[Affix grammar]]", "[[Alef (programming language)]]", "[[Aliasing (computing)]]"]
---

# Literal pool

In computer science, and specifically in compiler and assembler design, a literal pool is a lookup table used to hold literals during assembly and execution.
Multiple (local) literal pools are typically used only for computer architectures that lack branch instructions for long jumps, or have a set of instructions optimized for shorter jumps.  Examples of such architectures include the IBM System/360 and its successors, which had a number of instructions which took 12-bit address offsets.  In this case, the compiler would create a literal table on every 4K page; any branches whose target was less than 4K bytes away could be taken immediately; longer branches required an address lookup via the literal table.   The entries in the literal pool are placed into the object relocation table during assembly, and are then resolved at link edit time. 
The ARM architecture also makes use of multiple local pools, as does AArch64, the 64-bit extension to the original ARM.
Another architecture making use of multiple local pools is C-SKY, a 32-bit architecture designed for embedded SoCs.
In certain ways, a literal pool resembles a TOC or a global offset table (GOT), except that the implementation is considerably simpler, and there may be multiple literal tables per object.
Perhaps the most common type of literal pool are the literal pools used by the LDR Rd,=const pseudo-instruction in ARM assembly language
and similar instructions in IBM System/360 assembly language,
which are compiled to a LOAD with a PC-relative addressing mode and the constant stored in the literal pool.
On the IBM S/390 and zSeries architecture, the GNU assembler, "as" (which is invoked during the gcc build process) will use general-purpose register R13 to store a pointer to the literal pool.
Often some particular constant value will be used multiple times in a program.
Many linkers, by default, store each unique constant once, in a single combined literal pool; that improves code size.
The Java virtual machine has a "string literal pool" and a "class constant pool".

## Related

- [[Array-access analysis]]
- [[Metacompilation]]
- [[Semantic dictionary encoding]]
- [[Trace scheduling]]
- [[A-normal form]]
- [[Abstract syntax]]
- [[Access query language]]
- [[Affix grammar]]
- [[Alef (programming language)]]
- [[Aliasing (computing)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Literal_pool