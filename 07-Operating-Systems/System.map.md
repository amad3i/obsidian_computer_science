---
title: "System.map"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/System.map"
wikipedia_categories: ["Executable file formats", "Linux kernel"]
related: ["[[bss]]", "[[BogoMips]]", "[[Boot folder]]", "[[Booting process of Linux]]", "[[Configuration Menu Language]]", "[[Copy Fail]]", "[[Cryptoloop]]", "[[Debugfs]]", "[[Dirty COW]]", "[[Dprobes]]"]
---

# System.map

In Linux, the System.map file is a symbol table used by the kernel.
A symbol table is a look-up between symbol names and their addresses in memory. A symbol name may be the name of a variable or the name of a function. The System.map is required when the address of a symbol name, or the symbol name of an address, is needed. It is especially useful for debugging kernel panics and kernel oopses. The kernel does the address-to-name translation itself when CONFIG_KALLSYMS is enabled so that tools like ksymoops are not required.

## Related

- [[bss]]
- [[BogoMips]]
- [[Boot folder]]
- [[Booting process of Linux]]
- [[Configuration Menu Language]]
- [[Copy Fail]]
- [[Cryptoloop]]
- [[Debugfs]]
- [[Dirty COW]]
- [[Dprobes]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/System.map