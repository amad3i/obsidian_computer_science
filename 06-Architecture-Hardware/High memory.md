---
title: "High memory"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/High_memory"
wikipedia_categories: ["Linux kernel", "X86 architecture", "X86 memory management"]
related: ["[[BogoMips]]", "[[Boot folder]]", "[[Booting process of Linux]]", "[[Configuration Menu Language]]", "[[Copy Fail]]", "[[Cryptoloop]]", "[[Debugfs]]", "[[Dirty COW]]", "[[DL Boost]]", "[[Dprobes]]"]
---

# High memory

High memory is the part of physical memory in a computer which is not directly mapped by the page tables of its operating system kernel. The phrase is also sometimes used as shorthand for the High Memory Area, which is a different concept entirely.
Some operating system kernels, such as Linux, divide their virtual address space into two regions, devoting the larger to user space and the smaller to the kernel.  In current 32-bit x86 computers, this commonly (although does not have to, as this is a configurable option) takes the form of a 3GB/1GB split of the 4 GB address space, so kernel virtual addresses start at 0xC0000000 and go to 0xFFFFFFFF. The lower 896 MB, from 0xC0000000 to 0xF7FFFFFF, is directly mapped to the kernel physical address space, and the remaining 128 MB, from 0xF8000000 to 0xFFFFFFFF, is used on demand by the kernel to be mapped to high memory. When in user mode, translations are only effective for the first region, thus protecting the kernel from user programs, but when in kernel mode, translations are effective for both regions, thus giving the kernel an easy way to refer to the buffers of processes—it just uses the process' own mappings.
However, if the kernel needs to refer to physical memory for which a userspace translation has not already been provided, it has only 1 GB (for example) of virtual memory to use.  On computers with a lot of physical memory, this can mean that there exists memory that the kernel cannot refer to directly—this is called high memory. When the kernel wishes to address high memory, it creates a mapping on the fly and destroys the mapping when done, which incurs a performance penalty.

## Related

- [[BogoMips]]
- [[Boot folder]]
- [[Booting process of Linux]]
- [[Configuration Menu Language]]
- [[Copy Fail]]
- [[Cryptoloop]]
- [[Debugfs]]
- [[Dirty COW]]
- [[DL Boost]]
- [[Dprobes]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/High_memory