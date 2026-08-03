---
title: "Structured concurrency"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Structured_concurrency"
wikipedia_categories: ["Concurrent computing", "Programming paradigms"]
related: ["[[Choreographic programming]]", "[[Concurrent constraint logic programming]]", "[[Concurrent object-oriented programming]]", "[[Actor model]]", "[[Array programming]]", "[[Aspect-oriented programming]]", "[[Attribute-oriented programming]]", "[[Automata-based programming]]", "[[Automata-based programming (Shalyto's approach)]]", "[[Automatic programming]]"]
---

# Structured concurrency

Structured concurrency is a programming paradigm aimed at improving the clarity, quality, and development time of a computer program by using a structured approach to concurrent programming.
The core concept is the encapsulation of concurrent threads of execution (here encompassing kernel and userland threads and processes) by way of control flow constructs that have clear entry and exit points and that ensure all spawned threads have completed before exit. Such encapsulation allows errors in concurrent threads to be propagated to the control structure's parent scope and managed by the native error handling mechanisms of each particular computer language.  It allows control flow to remain readily evident by the structure of the source code despite the presence of concurrency. To be effective, this model must be applied consistently throughout all levels of the program – otherwise concurrent threads may leak out, become orphaned, or fail to have runtime errors correctly propagated.
Structured concurrency is analogous to structured programming, which uses control flow constructs that encapsulate sequential statements and subroutines.

## Related

- [[Choreographic programming]]
- [[Concurrent constraint logic programming]]
- [[Concurrent object-oriented programming]]
- [[Actor model]]
- [[Array programming]]
- [[Aspect-oriented programming]]
- [[Attribute-oriented programming]]
- [[Automata-based programming]]
- [[Automata-based programming (Shalyto's approach)]]
- [[Automatic programming]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Structured_concurrency