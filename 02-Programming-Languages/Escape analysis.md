---
title: "Escape analysis"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Escape_analysis"
wikipedia_categories: ["Static program analysis"]
related: ["[[Alias analysis]]", "[[Array-access analysis]]", "[[Call graph]]", "[[Code motion]]", "[[Dependence analysis]]", "[[Extended static checking]]", "[[Hoare logic]]", "[[Infer Static Analyzer]]", "[[Live-variable analysis]]", "[[Perl--Critic]]"]
---

# Escape analysis

In compiler optimization, escape analysis is a method for determining the dynamic scope of pointers –  where in the program a pointer can be accessed. It is related to pointer analysis and shape analysis.
When a variable (or an object) is allocated in a subroutine, a pointer to the variable can escape to other threads of execution, or to calling subroutines. If an implementation uses tail call optimization (usually required for functional languages), objects may also be seen as escaping to called subroutines. If a language supports first-class continuations (as do Scheme and Standard ML of New Jersey), portions of the call stack may also escape.
If a subroutine allocates an object and returns a pointer to it, the object can be accessed from undetermined places in the program –  the pointer has "escaped".  Pointers can also escape if they are stored in global variables or other data structures that, in turn, escape the current procedure.
Escape analysis determines all the places where a pointer can be stored and whether the lifetime of the pointer can be proven to be restricted only to the current procedure and/or thread.

## Related

- [[Alias analysis]]
- [[Array-access analysis]]
- [[Call graph]]
- [[Code motion]]
- [[Dependence analysis]]
- [[Extended static checking]]
- [[Hoare logic]]
- [[Infer Static Analyzer]]
- [[Live-variable analysis]]
- [[Perl--Critic]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Escape_analysis