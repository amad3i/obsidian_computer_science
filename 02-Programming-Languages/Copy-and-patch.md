---
title: "Copy-and-patch"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Copy-and-patch"
wikipedia_categories: ["Compiler construction"]
related: ["[[Abstract syntax]]", "[[Affix grammar]]", "[[Aliasing (computing)]]", "[[Array-access analysis]]", "[[Aspect weaver]]", "[[Attribute grammar]]", "[[Backus–Naur form]]", "[[Basic block]]", "[[Binary recompiler]]", "[[Bootstrapping (compilers)]]"]
---

# Copy-and-patch

In computing, copy-and-patch compilation is a simple compiler technique intended for just-in-time compilation (JIT compilation) that uses pattern matching to match pre-generated templates to parts of an abstract syntax tree (AST) or bytecode stream, and emit corresponding pre-written machine code fragments that are then patched to insert memory addresses, register addresses, constants and other parameters to produce executable code. Code not matched by templates can be either be interpreted in the normal way, or code created to directly call interpreter code.

## Related

- [[Abstract syntax]]
- [[Affix grammar]]
- [[Aliasing (computing)]]
- [[Array-access analysis]]
- [[Aspect weaver]]
- [[Attribute grammar]]
- [[Backus–Naur form]]
- [[Basic block]]
- [[Binary recompiler]]
- [[Bootstrapping (compilers)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Copy-and-patch