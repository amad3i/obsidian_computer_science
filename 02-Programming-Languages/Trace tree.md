---
title: "Trace tree"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Trace_tree"
wikipedia_categories: ["Compiler construction", "Trees (data structures)"]
related: ["[[Abstract syntax]]", "[[Abstract syntax tree]]", "[[Affix grammar]]", "[[Aliasing (computing)]]", "[[And–or tree]]", "[[Array-access analysis]]", "[[Aspect weaver]]", "[[Attribute grammar]]", "[[Backus–Naur form]]", "[[Ball tree]]"]
---

# Trace tree

A trace tree is a data structure that is used in the runtime compilation of programming code. Trace trees are used in tracing just-in-time compilation where tracing is used during code execution to look for hot spots before compilation. When those hot spots are entered again the compiled code is run instead. Each statement executed is traced, including within other function calls, and the entire execution path is compiled. This is different from compiling individual functions. More information can be gained allowing better compiler optimizations, including the removal of some function call overhead. The interpreter is called to continue whenever compiled code makes calls to code outside the compilation contexts.

## Related

- [[Abstract syntax]]
- [[Abstract syntax tree]]
- [[Affix grammar]]
- [[Aliasing (computing)]]
- [[And–or tree]]
- [[Array-access analysis]]
- [[Aspect weaver]]
- [[Attribute grammar]]
- [[Backus–Naur form]]
- [[Ball tree]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Trace_tree