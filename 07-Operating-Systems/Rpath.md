---
title: "Rpath"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Rpath"
wikipedia_categories: ["Computer libraries", "Operating system technology"]
related: ["[[Dynamic library]]", "[[Dynamic loading]]", "[[Library (computing)]]", "[[Position-independent code]]", "[[Shared library]]", "[[Accord.NET]]", "[[ALTQ]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Asynchronous system trap]]"]
---

# Rpath

In computer science, rpath designates the run-time search path hard-coded in an executable file or library. Dynamic linking loaders use the rpath to find required libraries.
Specifically, it encodes a path to shared libraries into the header of an executable (or another shared library).  This RPATH header value (so named in the Executable and Linkable Format header standards) may either override or supplement the system default dynamic linking search paths.
The rpath of an executable or shared library is an optional entry in the .dynamic section of the ELF executable or shared libraries, with the type DT_RPATH, called the DT_RPATH attribute. It can be stored there at link time by the linker. Tools such as chrpath and patchelf can create or modify the entry later.

## Related

- [[Dynamic library]]
- [[Dynamic loading]]
- [[Library (computing)]]
- [[Position-independent code]]
- [[Shared library]]
- [[Accord.NET]]
- [[ALTQ]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Asynchronous system trap]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Rpath