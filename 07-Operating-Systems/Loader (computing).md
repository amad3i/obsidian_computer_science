---
title: "Loader (computing)"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Loader_(computing)"
wikipedia_categories: ["Computer libraries", "Operating system kernels"]
related: ["[[Accord.NET]]", "[[Binary recompiler]]", "[[Compiler]]", "[[Dynamic library]]", "[[Dynamic linker]]", "[[Dynamic loading]]", "[[Feature Selection Toolbox]]", "[[Kernel (operating system)]]", "[[Kernel preemption]]", "[[Language binding]]"]
---

# Loader (computing)

In computing, a loader is the part of an operating system that is responsible for loading programs and libraries. It is one of the essential stages in the process of starting a program, as it places programs into memory and prepares them for execution. Loading a program involves either memory-mapping or copying the contents of the executable file containing the program instructions into memory, and then carrying out other required preparatory tasks to prepare the executable for running. Once loading is complete, the operating system starts the program by passing control to the loaded program code.
All operating systems that support program loading have loaders, apart from highly specialized computer systems that only have a fixed set of specialized programs. Embedded systems typically do not have loaders, and instead, the code executes directly from ROM or similar. In order to load the operating system itself, as part of booting, a specialized boot loader is used. In many operating systems, the loader resides permanently in memory, though some operating systems that support virtual memory may allow the loader to be located in a region of memory that is pageable.
In the case of operating systems that support virtual memory, the loader may not actually copy the contents of executable files into memory, but rather may simply declare to the virtual memory subsystem that there is a mapping between a region of memory allocated to contain the running program's code and the contents of the associated executable file. (See memory-mapped file.) The virtual memory subsystem is then made aware that pages with that region of memory need to be filled on demand if and when program execution actually hits those areas of unfilled memory. This may mean parts of a program's code are not actually copied into memory until they are actually used, and unused code may never be loaded into memory at all.

## Related

- [[Accord.NET]]
- [[Binary recompiler]]
- [[Compiler]]
- [[Dynamic library]]
- [[Dynamic linker]]
- [[Dynamic loading]]
- [[Feature Selection Toolbox]]
- [[Kernel (operating system)]]
- [[Kernel preemption]]
- [[Language binding]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Loader_(computing)