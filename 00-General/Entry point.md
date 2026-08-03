---
title: "Entry point"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Entry_point"
wikipedia_categories: ["Computer programming", "Control flow", "Software"]
related: ["[[Computer program]]", "[[Skeleton (computer programming)]]", "[[Algorave]]", "[[Asynchronous procedure call]]", "[[Asynchrony (computer programming)]]", "[[Bayesian program synthesis]]", "[[Boolean flag]]", "[[Breakpoint]]", "[[Cheat sheet]]", "[[Code Club]]"]
---

# Entry point

In computer programming, an entry point is the place in a program where the execution of a program begins, and where the program has access to command line arguments.
To start a program's execution, the loader or operating system passes control to its entry point. (During booting, the operating system itself is the program). This marks the transition from load time (and dynamic link time, if present) to run time.
For some operating systems and programming languages, the entry point is in a runtime library, a set of support functions for the language. The library code initializes the program and then passes control to the program proper. In other cases, the program may initialize the runtime library itself. 
In simple systems, execution begins at the first statement, which is common in interpreted languages, simple executable formats, and boot loaders. In other cases, the entry point is at some other known memory address which can be an absolute address or relative address (offset).
Alternatively, execution of a program can begin at a named point, either with a conventional name defined by the programming language or operating system or at a caller-specified name. In many C-family languages, this is a function called main; as a result, the entry point is often known as the main function.
In JVM languages, such as Java, the entry point is a static method called main; in CLI languages such as C# the entry point is a static method named Main.

## Related

- [[Computer program]]
- [[Skeleton (computer programming)]]
- [[Algorave]]
- [[Asynchronous procedure call]]
- [[Asynchrony (computer programming)]]
- [[Bayesian program synthesis]]
- [[Boolean flag]]
- [[Breakpoint]]
- [[Cheat sheet]]
- [[Code Club]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Entry_point