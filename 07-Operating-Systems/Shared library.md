---
title: "Shared library"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Shared_library"
wikipedia_categories: ["Computer libraries", "Operating system technology"]
related: ["[[Dynamic library]]", "[[Dynamic loading]]", "[[Library (computing)]]", "[[Position-independent code]]", "[[Rpath]]", "[[Accord.NET]]", "[[ALTQ]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Asynchronous system trap]]"]
---

# Shared library

A shared library is a library of executable code that is loaded in memory such that multiple executables (programs and other libraries) can use it at runtime.
In contrast, a static library is copied into an executable. A static library can be re-used (a form of sharing) in multiple executables, but each executable contains a copy of the library code instead of 
sharing a copy in memory with other executables. Although not true today, historically, all libraries were static. Although a shared library can have static linkage, such a library is not classified as a static library.
Often, a shared library is also a dynamic library loaded by a dynamic linker, which generally makes use of the library easier for the programmer than if it instead it had static linkage. A dynamic library need not be accessible to multiple executables (shared library) and a shared library need not be loaded at consumer runtime (dynamic library).

## Related

- [[Dynamic library]]
- [[Dynamic loading]]
- [[Library (computing)]]
- [[Position-independent code]]
- [[Rpath]]
- [[Accord.NET]]
- [[ALTQ]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Asynchronous system trap]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Shared_library