---
title: "Position-independent code"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Position-independent_code"
wikipedia_categories: ["Computer file formats", "Computer libraries", "Operating system technology"]
related: ["[[Dynamic library]]", "[[Dynamic loading]]", "[[Library (computing)]]", "[[Rpath]]", "[[Shared library]]", "[[wps]]", "[[Accord.NET]]", "[[ALTQ]]", "[[ANSI 834 Enrollment Implementation Format]]", "[[Application binary interface]]"]
---

# Position-independent code

In computing, position-independent code (PIC) or position-independent executable (PIE) is a body of machine code that executes properly regardless of its memory address. PIC is commonly used for shared libraries, so that the same library code can be loaded at a location in each program's address space where it does not overlap with other memory in use by, for example, other shared libraries. PIC was also used on older computer systems that lacked a Memory Management Unit (MMU), so that the operating system could keep applications away from each other even within the single address space of an MMU-less system.
Position-independent code can be executed at any memory address without modification. This differs from absolute code, which must be loaded at a specific location to function correctly, and load-time locatable (LTL) code, in which a linker or program loader modifies a program before execution, so it can be run only from a particular memory location. The latter terms are sometimes referred to as position-dependent code. Generating position-independent code is often the default behavior for compilers, but they may place restrictions on the use of some language features, such as disallowing use of absolute addresses (position-independent code has to use relative addressing). Instructions that refer directly to specific memory addresses sometimes execute faster, and replacing them with equivalent relative-addressing instructions may result in slightly slower execution, although modern processors make the difference practically negligible.

## Related

- [[Dynamic library]]
- [[Dynamic loading]]
- [[Library (computing)]]
- [[Rpath]]
- [[Shared library]]
- [[wps]]
- [[Accord.NET]]
- [[ALTQ]]
- [[ANSI 834 Enrollment Implementation Format]]
- [[Application binary interface]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Position-independent_code