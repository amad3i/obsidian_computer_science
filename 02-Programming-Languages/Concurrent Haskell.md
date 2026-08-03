---
title: "Concurrent Haskell"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Concurrent_Haskell"
wikipedia_categories: ["1996 software", "Cross-platform free software", "Free and open source compilers", "Free software programmed in Haskell", "Functional languages", "Haskell programming language family", "Programming languages", "Programming languages created in 1996"]
related: ["[[Atom (programming language)]]", "[[Agda (programming language)]]", "[[Red (programming language)]]", "[[Scala (programming language)]]", "[[Squeak]]", "[[V (programming language)]]", "[[Ciao (programming language)]]", "[[Crystal (programming language)]]", "[[Cuneiform (programming language)]]", "[[Erlang (programming language)]]"]
---

# Concurrent Haskell

Concurrent Haskell (also Control.Concurrent, or Concurrent and Parallel Haskell) is an extension to the functional programming language Haskell, which adds explicit primitive data types for concurrency. It was first added to Haskell 98, and has since become a library named Control.Concurrent included as part of the Glasgow Haskell Compiler.
Its two main underlying concepts are:

A primitive data type MVar α implementing a bounded/single-place asynchronous channel, which is either empty or holds a value of type α.
The ability to spawn a concurrent thread via the forkIO primitive.
Built on this is a set of useful concurrency and synchronizing abstractions such as unbounded channels, semaphores and sample variables.
Haskell threads have very low overhead: creating, context-switching, and scheduling are all internal to the Haskell runtime system. These Haskell-level threads are mapped onto a configurable number of operating system (OS) level threads, usually one per processor core.

## Related

- [[Atom (programming language)]]
- [[Agda (programming language)]]
- [[Red (programming language)]]
- [[Scala (programming language)]]
- [[Squeak]]
- [[V (programming language)]]
- [[Ciao (programming language)]]
- [[Crystal (programming language)]]
- [[Cuneiform (programming language)]]
- [[Erlang (programming language)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Concurrent_Haskell