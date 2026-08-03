---
title: "Link time"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Link_time"
wikipedia_categories: ["Compiler construction"]
related: ["[[Abstract syntax]]", "[[Affix grammar]]", "[[Aliasing (computing)]]", "[[Array-access analysis]]", "[[Aspect weaver]]", "[[Attribute grammar]]", "[[Backus–Naur form]]", "[[Basic block]]", "[[Binary recompiler]]", "[[Bootstrapping (compilers)]]"]
---

# Link time

In computing, link time is the duration of time when a linker is creating an executable. Link time is a phase in the operational life cycle of a program as it transitions from development to execution. It occurs after compilation (compile time) and before execution (run time).
Operations performed at link time usually include fixing up the addresses of externally referenced objects and functions, various kinds of cross module checks (e.g. type checks on externally visible  identifiers and in some languages instantiation of templates). Some optimizing compilers delay code generation until link time because it is here that information about a complete program is available to them. Resolving external variables in a program is also done at link time. The liker may also perform optimizations.
The definition of a programming language may specify link time requirements that must be met (e.g. the maximum number of characters in an externally visible identifier that must be considered significant). It is common to speak of link time operations (the operations performed by a linker) or link time requirements (programming language requirements that must be met by compiled source code for it to be successfully linked).
In some programming languages it may be necessary for some compilation and linking to occur at runtime.

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

- Wikipedia: https://en.wikipedia.org/wiki/Link_time