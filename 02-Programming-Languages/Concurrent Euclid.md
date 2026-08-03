---
title: "Concurrent Euclid"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Concurrent_Euclid"
wikipedia_categories: ["Concurrent programming languages"]
related: ["[[-Lisp]]", "[[Actor-Based Concurrent Language]]", "[[AgentSheets]]", "[[Alef (programming language)]]", "[[Algorithmic skeleton]]", "[[AmbientTalk]]", "[[Ateji PX]]", "[[Axum (programming language)]]", "[[Ballerina (programming language)]]", "[[C-]]"]
---

# Concurrent Euclid

Concurrent Euclid (ConEuc) is a concurrent descendant of the Euclid programming language designed by James Cordy and Ric Holt, then at the University of Toronto, in 1980.  ConEuc was designed for concurrent, high performance, highly reliable system software, such as operating systems, compilers and embedded microprocessor systems. The TUNIS operating system, a Unix variant, was implemented entirely in Concurrent Euclid. ConEuc extends a core subset of Euclid with  processes and monitors (as specified by C.A.R. Hoare) as well as language constructs needed for systems programming including separate compilation, variables at absolute addresses, type converters, long integers and other features.
ConEuc was implemented by a small (50k bytes), fast, portable compiler that was self-compiling and had replaceable code generators. High quality code generators for several computers, including the PDP-11, VAX-11, Motorola 68000 and Motorola 6809 were developed that produced code comparable to the best C compilers. Concurrent Euclid programs that used concurrency could be run on a bare machine (supported by a small assembly language kernel), or in simulated mode as an ordinary process running under an operating system.
The Turing programming language is a direct descendant of Concurrent Euclid and its Turing Plus variant eventually replaced ConEuc in most applications.

## Related

- [[-Lisp]]
- [[Actor-Based Concurrent Language]]
- [[AgentSheets]]
- [[Alef (programming language)]]
- [[Algorithmic skeleton]]
- [[AmbientTalk]]
- [[Ateji PX]]
- [[Axum (programming language)]]
- [[Ballerina (programming language)]]
- [[C-]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Concurrent_Euclid