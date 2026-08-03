---
title: "Dead code"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Dead_code"
wikipedia_categories: ["Compiler construction", "Software anomalies", "Source code"]
related: ["[[Abstract syntax]]", "[[Affix grammar]]", "[[Aliasing (computing)]]", "[[Array-access analysis]]", "[[Aspect weaver]]", "[[Attribute grammar]]", "[[Backus–Naur form]]", "[[Basic block]]", "[[Binary recompiler]]", "[[Bootstrapping (compilers)]]"]
---

# Dead code

The term dead code has multiple definitions. Some use the term to refer to code (i.e. instructions in memory) which can never be executed at run-time.
In some areas of computer programming, dead code is a section in the source code of a program which is executed but whose result is never used in any other computation. The execution of dead code wastes computation time and memory.
While the result of a dead computation may never be used, it may raise exceptions or affect some global state, thus removal of such code may change the output of the program and introduce unintended bugs. Compiler optimizations are typically conservative in their approach to dead-code removal if there is any ambiguity as to whether removal of the dead code will affect the program output. The programmer may aid the compiler in this matter by making additional use of static and/or inline functions and enabling the use of link-time optimization.

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

- Wikipedia: https://en.wikipedia.org/wiki/Dead_code