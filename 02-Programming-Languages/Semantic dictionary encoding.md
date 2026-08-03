---
title: "Semantic dictionary encoding"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Semantic_dictionary_encoding"
wikipedia_categories: ["Compiler construction", "Computational linguistics stubs", "Computer science stubs", "Programming language theory", "Programming language topic stubs", "Semantics"]
related: ["[[Qualification principle]]", "[[Typed assembly language]]", "[[Abstract syntax]]", "[[Array-access analysis]]", "[[Computational semantics]]", "[[Divergence (computer science)]]", "[[First-class function]]", "[[Literal pool]]", "[[Logic of Computable Functions]]", "[[Meta-tracing]]"]
---

# Semantic dictionary encoding

Semantic dictionary encoding (SDE) preserves the full semantic context of source programs while adding further information that can be used for accelerating the speed of code generation. SDE forms a code-generating loader. It is a form of bytecode combined with a JIT compiler. It is code generation at load time.
In an elementary form, the dictionary entries represent nodes in a directed acyclic graph (DAG), that describes the actions of the program, as an abstract syntax tree (AST) in tabular form.
It uses an intermediate representation (IR), that is based on the encoded abstract syntax tree and symbol table of a program.

## Related

- [[Qualification principle]]
- [[Typed assembly language]]
- [[Abstract syntax]]
- [[Array-access analysis]]
- [[Computational semantics]]
- [[Divergence (computer science)]]
- [[First-class function]]
- [[Literal pool]]
- [[Logic of Computable Functions]]
- [[Meta-tracing]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Semantic_dictionary_encoding