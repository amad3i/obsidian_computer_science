---
title: "Global Offset Table"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Global_Offset_Table"
wikipedia_categories: ["Computer programming", "Computer programming stubs"]
related: ["[[Asynchronous procedure call]]", "[[Code Words]]", "[[Glue code]]", "[[Opaque predicate]]", "[[Procedural design]]", "[[Action–domain–responder]]", "[[Active object]]", "[[Aggregate pattern]]", "[[Algorave]]", "[[Association (object-oriented programming)]]"]
---

# Global Offset Table

The Global Offset Table, or GOT, is a section of a computer program's (executables and shared libraries) memory used to enable computer program code compiled as an ELF file to run correctly, independent of the memory address where the program's code or data is loaded at runtime.
It maps symbols in programming code to their corresponding absolute memory addresses to facilitate Position Independent Code (PIC) and Position Independent Executables (PIE) which are loaded to a different memory address each time the program is started. The runtime memory address, also known as absolute memory address of variables and functions is unknown before the program is started when PIC or PIE code is run so cannot be hardcoded during compilation by a compiler.
The Global Offset Table is represented as the .got and .got.plt sections in an ELF file which are loaded into the program's memory at startup. The operating system's dynamic linker updates the global offset table relocations (symbol to absolute memory addresses) at program startup or as symbols are accessed.
It is the mechanism that allows shared libraries (.so) to be relocated to a different memory address at startup and avoid memory address conflicts with the main program or other shared libraries, and to harden computer program code from exploitation.

## Related

- [[Asynchronous procedure call]]
- [[Code Words]]
- [[Glue code]]
- [[Opaque predicate]]
- [[Procedural design]]
- [[Action–domain–responder]]
- [[Active object]]
- [[Aggregate pattern]]
- [[Algorave]]
- [[Association (object-oriented programming)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Global_Offset_Table