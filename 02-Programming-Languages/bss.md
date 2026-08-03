---
title: ".bss"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/.bss"
wikipedia_categories: ["Assembly languages", "Executable file formats", "Memory management", "Programming language implementation"]
related: ["[[Assembly language]]", "[[Object file]]", "[[Address constant]]", "[[Addressing mode]]", "[[ARB assembly language]]", "[[Aspect weaver]]", "[[Autocoder]]", "[[Bit numbering]]", "[[Common Intermediate Language]]", "[[COMPASS]]"]
---

# .bss

In computer programming, the block starting symbol (abbreviated to .bss or bss) is the portion of an object file, executable, or assembly language code that contains statically allocated variables that are declared but have not been assigned a value yet. It is often referred to as the "bss section" or "bss segment".
Typically only the length of the bss section, but no data, is stored in the object file. The program loader allocates memory for the bss section when it loads the program. By placing variables with no value in the .bss section, instead of the .data or .rodata section which require initial value data, the size of the object file is reduced.
On some platforms, some or all of the bss section is initialized to zeroes. Unix-like systems and Windows initialize the bss section to zero, which can thus be used for C and C++ statically allocated variables that are initialized to all zero bits. Operating systems may use a technique called zero-fill-on-demand to efficiently implement the bss segment.  In embedded software, the bss segment is mapped into memory that is initialized to zero by the C run-time system before main() is entered. Some C run-time systems may allow part of the bss segment not to be initialized; C variables must explicitly be placed into that portion of the bss segment.
On some computer architectures, the application binary interface also supports an sbss segment for "small data".  Typically, these data items can be accessed using shorter instructions that may only be able to access a certain range of addresses. Architectures supporting thread-local storage might use a tbss section for uninitialized, static data marked as thread-local.

## Related

- [[Assembly language]]
- [[Object file]]
- [[Address constant]]
- [[Addressing mode]]
- [[ARB assembly language]]
- [[Aspect weaver]]
- [[Autocoder]]
- [[Bit numbering]]
- [[Common Intermediate Language]]
- [[COMPASS]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/.bss