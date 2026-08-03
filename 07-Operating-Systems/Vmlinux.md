---
title: "Vmlinux"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Vmlinux"
wikipedia_categories: ["Linux kernel"]
related: ["[[BogoMips]]", "[[Boot folder]]", "[[Booting process of Linux]]", "[[Configuration Menu Language]]", "[[Copy Fail]]", "[[Cryptoloop]]", "[[Debugfs]]", "[[Dirty COW]]", "[[Dprobes]]", "[[Dracut (software)]]"]
---

# Vmlinux

vmlinux (Virtual Memory Linux) is a statically linked executable file that contains the Linux kernel in one of the object file formats supported by Linux, which includes Executable and Linkable Format (ELF) and Common Object File Format (COFF). The vmlinux file might be required for kernel debugging, symbol table generation or other operations, but must be made bootable before being used as an operating system kernel by adding a multiboot header, bootsector and setup routines. vmlinuz is the compressed version of vmlinux.

## Related

- [[BogoMips]]
- [[Boot folder]]
- [[Booting process of Linux]]
- [[Configuration Menu Language]]
- [[Copy Fail]]
- [[Cryptoloop]]
- [[Debugfs]]
- [[Dirty COW]]
- [[Dprobes]]
- [[Dracut (software)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Vmlinux