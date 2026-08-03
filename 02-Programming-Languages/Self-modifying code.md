---
title: "Self-modifying code"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Self-modifying_code"
wikipedia_categories: ["Programming paradigms"]
related: ["[[Array programming]]", "[[Aspect-oriented programming]]", "[[Attribute-oriented programming]]", "[[Automata-based programming]]", "[[Automata-based programming (Shalyto's approach)]]", "[[Automatic programming]]", "[[Choreographic programming]]", "[[Comparison of multi-paradigm programming languages]]", "[[Concurrent constraint logic programming]]", "[[Concurrent logic programming]]"]
---

# Self-modifying code

In computer science, self-modifying code (SMC or SMoC) is code that alters its own instructions while it is executing – usually to reduce the instruction path length and improve performance or simply to reduce otherwise repetitively similar code, thus simplifying maintenance. The term is usually only applied to code where the self-modification is intentional, not in situations where code accidentally modifies itself due to an error such as a buffer overflow.
Self-modifying code can involve overwriting existing instructions or generating new code at run time and transferring control to that code.
Self-modification can be used as an alternative to the method of "flag setting" and conditional program branching, used primarily to reduce the number of times a condition needs to be tested.
The method is frequently used for conditionally invoking test/debugging code without requiring additional computational overhead for every input/output cycle.
The modifications may be performed:

only during initialization – based on input parameters (when the process is more commonly described as software "configuration" and is somewhat analogous, in hardware terms, to setting jumpers for printed circuit boards). Alteration of program entry pointers is an equivalent indirect method of self-modification, but requiring the co-existence of one or more alternative instruction paths, increasing the program size.
throughout execution ("on the fly") – based on particular program states that have been reached during the execution
In either case, the modifications may be performed directly to the machine code instructions themselves, by overlaying new instructions over the existing ones (for example, altering a compare and branch to an unconditional branch or alternatively a NOP).
In the IBM System/360 architecture and its successors up to z/Architecture, an EXECUTE (EX) instruction logically overlays the second byte of its target instruction with the low-order 8 bits of register 1. This provides the effect of self-modification, although the actual instruction in storage is not altered.

## Related

- [[Array programming]]
- [[Aspect-oriented programming]]
- [[Attribute-oriented programming]]
- [[Automata-based programming]]
- [[Automata-based programming (Shalyto's approach)]]
- [[Automatic programming]]
- [[Choreographic programming]]
- [[Comparison of multi-paradigm programming languages]]
- [[Concurrent constraint logic programming]]
- [[Concurrent logic programming]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Self-modifying_code