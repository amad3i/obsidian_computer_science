---
title: "Compile-time function execution"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Compile-time_function_execution"
wikipedia_categories: ["Compiler construction", "Compiler optimizations"]
related: ["[[Optimizing compiler]]", "[[Trace scheduling]]", "[[Abstract syntax]]", "[[Affix grammar]]", "[[Aliasing (computing)]]", "[[Array-access analysis]]", "[[Aspect weaver]]", "[[Attribute grammar]]", "[[Automatic parallelization]]", "[[Automatic vectorization]]"]
---

# Compile-time function execution

In computing, compile-time function execution (or compile-time function evaluation, or general constant expressions) is the ability of a compiler, that would normally compile a function to machine code and execute it at run time, to execute the function at compile time. This is possible if the arguments to the function are known at compile time, and the function does not make any reference to or attempt to modify any global state (i.e. it is a pure function).
If the value of only some of the arguments are known, the compiler may still be able to perform some level of compile-time function execution (partial evaluation), possibly producing more optimized code than if no arguments were known.

## Related

- [[Optimizing compiler]]
- [[Trace scheduling]]
- [[Abstract syntax]]
- [[Affix grammar]]
- [[Aliasing (computing)]]
- [[Array-access analysis]]
- [[Aspect weaver]]
- [[Attribute grammar]]
- [[Automatic parallelization]]
- [[Automatic vectorization]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Compile-time_function_execution