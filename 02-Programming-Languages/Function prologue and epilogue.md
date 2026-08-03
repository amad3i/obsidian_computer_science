---
title: "Function prologue and epilogue"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Function_prologue_and_epilogue"
wikipedia_categories: ["Assembly languages", "Subroutines"]
related: ["[[bss]]", "[[Address constant]]", "[[Addressing mode]]", "[[Anonymous function]]", "[[ARB assembly language]]", "[[Assembly language]]", "[[Autocoder]]", "[[Bit numbering]]", "[[Common Intermediate Language]]", "[[COMPASS]]"]
---

# Function prologue and epilogue

In assembly language programming, the function prologue is a few lines of code at the beginning of a function, which prepare the stack and registers for use within the function. Similarly, the function epilogue appears at the end of the function, and restores the stack and registers to the state they were in before the function was called.
The prologue and epilogue are not a part of the assembly language itself; they represent a convention used by assembly language programmers, and compilers of many higher-level languages.  They are fairly rigid, having the same form in each function.
Function prologue and epilogue also sometimes contain code for buffer overflow protection.

## Related

- [[bss]]
- [[Address constant]]
- [[Addressing mode]]
- [[Anonymous function]]
- [[ARB assembly language]]
- [[Assembly language]]
- [[Autocoder]]
- [[Bit numbering]]
- [[Common Intermediate Language]]
- [[COMPASS]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Function_prologue_and_epilogue