---
title: "Single address space operating system"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Single_address_space_operating_system"
wikipedia_categories: ["Computer engineering stubs", "Operating systems"]
related: ["[[Bare machine]]", "[[Comparison of operating systems]]", "[[Comparison of user features of operating systems]]", "[[DBOS]]", "[[Distributed operating system]]", "[[Earcon]]", "[[ECSE (Academic Degree)]]", "[[Error guessing]]", "[[Glossary of operating systems terms]]", "[[HashClash]]"]
---

# Single address space operating system

In computer science, a single address space operating system (or SASOS) is an operating system that provides only one globally shared address space for all processes. In a single address space operating system, numerically identical (virtual memory) logical addresses in different processes all refer to exactly the same byte of data.
In a traditional OS with private per-process address space, memory protection is based on address space boundaries ("address space isolation"). Single address-space operating systems make translation and protection orthogonal, which in no way weakens protection. 
The core advantage is that pointers (i.e. memory references) have global validity, meaning their meaning is independent of the process using it. This allows sharing pointer-connected data structures across processes, and making them persistent, i.e. storing them on backup store.
Some processor architectures have direct support for protection independent of translation. On such architectures, a SASOS may be able to perform context switches faster than a traditional OS. Such architectures include Itanium, and Version 5 of the Arm architecture, as well as capability architectures such as CHERI.
A SASOS should not be confused with a flat memory model, which provides no address translation and generally no memory protection. In contrast, a SASOS makes protection orthogonal to translation: it may be possible to name a data item (i.e. know its virtual address) while not being able to access it.
SASOS projects using hardware-based protection include the following:

Angel
IBM i (formerly called OS/400)
Iguana at NICTA, Australia
Mungi at NICTA, Australia
Nemesis
Opal
Scout
Sombrero
Related are OSes that provide protection through language-level type safety:

Br1X
Genera
JX a research Java OS
Phantom OS
Singularity
Theseus OS
Torsion

## Related

- [[Bare machine]]
- [[Comparison of operating systems]]
- [[Comparison of user features of operating systems]]
- [[DBOS]]
- [[Distributed operating system]]
- [[Earcon]]
- [[ECSE (Academic Degree)]]
- [[Error guessing]]
- [[Glossary of operating systems terms]]
- [[HashClash]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Single_address_space_operating_system