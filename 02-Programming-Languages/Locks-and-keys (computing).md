---
title: "Locks-and-keys (computing)"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Locks-and-keys_(computing)"
wikipedia_categories: ["Computer programming", "Programming language topic stubs"]
related: ["[[Fluxus (programming environment)]]", "[[Self-documenting code]]", "[[Sonic Pi]]", "[[A-normal form]]", "[[Access query language]]", "[[Alef (programming language)]]", "[[Algorave]]", "[[Alpha (programming language)]]", "[[Array-access analysis]]", "[[Asynchronous procedure call]]"]
---

# Locks-and-keys (computing)

Locks-and-keys is a solution to dangling pointers in computer programming languages.
The locks-and-keys approach represents pointers as ordered pairs (key, address) where the key is an integer value. Heap-dynamic variables are represented as the storage for the variable plus a cell for an integer lock value. When a variable is allocated, a lock value is created and placed both into the variable's cell and into the pointer's key cell. Every access to the pointer compares these two values, and access is allowed only if the values match.
When a variable is deallocated, the key of its pointer is modified to hold a value different from the variable's cell. From then on, any attempt to dereference the pointer can be flagged as an error. Since copying a pointer also copies its cell value, changing the key of the ordered pair safely disables all copies of the pointer.

## Related

- [[Fluxus (programming environment)]]
- [[Self-documenting code]]
- [[Sonic Pi]]
- [[A-normal form]]
- [[Access query language]]
- [[Alef (programming language)]]
- [[Algorave]]
- [[Alpha (programming language)]]
- [[Array-access analysis]]
- [[Asynchronous procedure call]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Locks-and-keys_(computing)