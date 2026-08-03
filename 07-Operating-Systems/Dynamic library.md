---
title: "Dynamic library"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Dynamic_library"
wikipedia_categories: ["Computer libraries", "Operating system technology"]
related: ["[[Dynamic loading]]", "[[Library (computing)]]", "[[Position-independent code]]", "[[Rpath]]", "[[Shared library]]", "[[Accord.NET]]", "[[ALTQ]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Asynchronous system trap]]"]
---

# Dynamic library

A dynamic library is a library that contains functions and data that can be used by a computer program at run-time as loaded from a file separate from the program executable. Dynamic linking or late binding allows for using a dynamic library by linking program library references with the associated objects in the library either at load-time or run-time. At program build-time, the linker records what library objects the program uses. When the program is run, a dynamic linker or linking loader associates program library references with the associated objects in the library. 
A dynamic library can be linked at build-time to a stub for each library resource that is resolved at run-time. Alternatively, a dynamic library can be loaded without linking to stubs.
Most modern operating systems use the same format for both a dynamic library and an executable which affords two main advantages: it necessitates only one loader, and it allows an executable file to be used as a shared library. Examples of file formats use for both dynamic library and executable files include ELF, Mach-O, and PE.
A dynamic library is called by different names in different contexts. In Windows and OS/2 the technology is called dynamic-link library. In Unix-like user space, it's called dynamic shared object (DSO), or usually just shared object (SO). In Linux kernel it's called loadable kernel module (LKM). In OpenVMS, it's called shareable image.
As an alternative to dynamic linking, a static library is included into the program executable so that the library is not required at run-time.

## Related

- [[Dynamic loading]]
- [[Library (computing)]]
- [[Position-independent code]]
- [[Rpath]]
- [[Shared library]]
- [[Accord.NET]]
- [[ALTQ]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Asynchronous system trap]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dynamic_library