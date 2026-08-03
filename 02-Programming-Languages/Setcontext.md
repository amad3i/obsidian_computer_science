---
title: "Setcontext"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Setcontext"
wikipedia_categories: ["C (programming language) libraries", "Control flow", "Threads (computing)", "Unix"]
related: ["[[ACM SIGOPS Annual Technical Conference]]", "[[Asynchronous method invocation]]", "[[C (programming language)]]", "[[Code cave]]", "[[Concurrent object-oriented programming]]", "[[Entry point]]", "[[Exception handling]]", "[[Gecos field]]", "[[Group identifier]]", "[[Input Field Separators]]"]
---

# Setcontext

setcontext is one of a family of C library functions (the others being getcontext, makecontext and swapcontext) used for context control. The setcontext family allows the implementation in C of advanced control flow patterns such as iterators, fibers, and coroutines. They may be viewed as an advanced version of setjmp/longjmp; whereas the latter allows only a single non-local jump up the stack, setcontext allows the creation of multiple cooperative threads of control, each with its own stack.

## Related

- [[ACM SIGOPS Annual Technical Conference]]
- [[Asynchronous method invocation]]
- [[C (programming language)]]
- [[Code cave]]
- [[Concurrent object-oriented programming]]
- [[Entry point]]
- [[Exception handling]]
- [[Gecos field]]
- [[Group identifier]]
- [[Input Field Separators]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Setcontext