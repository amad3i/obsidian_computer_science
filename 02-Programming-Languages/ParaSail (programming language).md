---
title: "ParaSail (programming language)"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/ParaSail_(programming_language)"
wikipedia_categories: ["2009 software", "Concurrent programming languages", "Cross-platform software", "Free software projects", "Pascal programming language family", "Procedural programming languages", "Programming languages created in 2009", "Systems programming languages"]
related: ["[[Go (programming language)]]", "[[Chapel (programming language)]]", "[[Nim (programming language)]]", "[[Rust (programming language)]]", "[[V (programming language)]]", "[[C (programming language)]]", "[[CoffeeScript]]", "[[CS-4 (programming language)]]", "[[D (programming language)]]", "[[Joyce (programming language)]]"]
---

# ParaSail (programming language)

Parallel Specification and Implementation Language (ParaSail) is an object-oriented parallel programming language.  Its design and ongoing implementation is described in a blog and on its official website.
ParaSail uses a pointer-free programming model, where objects can grow and shrink, and value semantics are used for assignment.  It has no global garbage collected heap.  Instead, region-based memory management is used throughout. Types can be recursive, so long as the recursive components are declared optional. There are no global variables, no parameter aliasing, and all subexpressions of an expression can be evaluated in parallel. Assertions, preconditions, postconditions, class invariants, etc., are part of the standard syntax, using a Hoare-like notation. Any possible race conditions are detected at compile time. 
Initial design of ParaSail began in September 2009, by S. Tucker Taft.
Both an interpreter using the ParaSail virtual machine, and an LLVM-based ParaSail compiler are available.  Work stealing is used for scheduling ParaSail's light-weight threads. The latest version can be downloaded from the ParaSail website.

## Related

- [[Go (programming language)]]
- [[Chapel (programming language)]]
- [[Nim (programming language)]]
- [[Rust (programming language)]]
- [[V (programming language)]]
- [[C (programming language)]]
- [[CoffeeScript]]
- [[CS-4 (programming language)]]
- [[D (programming language)]]
- [[Joyce (programming language)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/ParaSail_(programming_language)