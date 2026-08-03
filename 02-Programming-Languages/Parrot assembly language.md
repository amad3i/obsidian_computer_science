---
title: "Parrot assembly language"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Parrot_assembly_language"
wikipedia_categories: ["Assembly languages", "Perl"]
related: ["[[Parrot intermediate representation]]", "[[bss]]", "[[ActivePerl]]", "[[Address constant]]", "[[Addressing mode]]", "[[ARB assembly language]]", "[[Assembly language]]", "[[Autocoder]]", "[[Bit numbering]]", "[[Common Intermediate Language]]"]
---

# Parrot assembly language

The Parrot assembly language (PASM) is an assembly language for the Parrot virtual machine.
PASM is the lowest level assembly language in the Parrot stack. The Parrot intermediate representation (PIR) is PASM extended to simplify development of compilers.
The hello world program in PASM is simply:

print "Hello world!\n"
end

Although it appears similar to source code in some high-level programming languages, more complex PASM programs will resemble other assembly languages. The main exceptions to this low level programming in PASM are string handling and, as shown above, input and output. Additionally, PASM has automatic garbage collection from the virtual machine, and it does not allow pointer arithmetic.
Parrot assembly language has more instructions than hardware assembly languages, even  CISC processors. This is because the marginal cost of creating a new instruction in Parrot is low compared to the marginal cost of doing so in hardware, and the creators of Parrot had no particular goal of minimalism.

## Related

- [[Parrot intermediate representation]]
- [[bss]]
- [[ActivePerl]]
- [[Address constant]]
- [[Addressing mode]]
- [[ARB assembly language]]
- [[Assembly language]]
- [[Autocoder]]
- [[Bit numbering]]
- [[Common Intermediate Language]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Parrot_assembly_language