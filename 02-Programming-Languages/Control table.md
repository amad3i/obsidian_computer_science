---
title: "Control table"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Control_table"
wikipedia_categories: ["Compiler construction", "Compiler structures"]
related: ["[[Abstract syntax]]", "[[Affix grammar]]", "[[Aliasing (computing)]]", "[[Array-access analysis]]", "[[Aspect weaver]]", "[[Attribute grammar]]", "[[Backus–Naur form]]", "[[Basic block]]", "[[Binary recompiler]]", "[[Bootstrapping (compilers)]]"]
---

# Control table

A control table is a table data structure (i.e. array of records) used to direct the control flow of a computer program. Software that uses a control table is said to be table-driven. A control table encodes both the parameters to a conditional expression and a function reference. An interpreter processes a table by evaluating the conditional expression for input data and invoking the selected function. Using a control table can reduce the need for repetitive code that implements the same logic.
In general, the mapping of input parameters can be via any data structure. A common data structure is the lookup, which provides relatively high performance but at a relatively high memory footprint. An associative array can minimize memory use at the cost of more lookup time.
How the associated behavior is referenced varies. Some languages provide a direct function reference (i.e. pointer) that can be used to invoke a function directly, but some languages do not. Some languages provide for jumping to a location (i.e.label). As a fallback, any language allows for mapping input to an index that can then be used to branch to a particular part of the code.
A control table is often used as part of a higher-level algorithm. It can control the main loop of an event-driven program. A relatively advanced use is instructions for a virtual machine – similar to bytecode but usually with operations implied by the table structure itself instead of encoded in the table data.

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

- Wikipedia: https://en.wikipedia.org/wiki/Control_table