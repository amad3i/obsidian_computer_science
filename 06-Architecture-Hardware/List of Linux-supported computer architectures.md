---
title: "List of Linux-supported computer architectures"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/List_of_Linux-supported_computer_architectures"
wikipedia_categories: ["Linux kernel"]
related: ["[[BogoMips]]", "[[Boot folder]]", "[[Booting process of Linux]]", "[[Configuration Menu Language]]", "[[Copy Fail]]", "[[Cryptoloop]]", "[[Debugfs]]", "[[Dirty COW]]", "[[Dprobes]]", "[[Dracut (software)]]"]
---

# List of Linux-supported computer architectures

The basic components of the Linux family of operating systems, which are based on the Linux kernel, the GNU C Library,  BusyBox or forks thereof like μClinux and uClibc, have been programmed with a certain level of abstraction in mind. Also, there are distinct code paths in the assembly language or C source code which support certain hardware. Therefore, the source code can be successfully compiled on‍—‌or cross-compiled for‍—‌a great number of computer architectures.
Furthermore, the required free and open-source software has also been developed to interface between Linux and the hardware Linux is to be executed on.  For example, compilers are available, e.g. GNU Compiler Collection (GCC) and LLVM/Clang. For cross-compilation a number of complete toolchains are available, like GNU toolchain, OpenWrt (Buildroot), and OpenEmbedded. The Yocto Project is targeted at embedded use cases.
The portability section of the Linux kernel article contains information and references to technical details.
Note that further components like a windowing system, or programs like Blender, can be present or absent. Fundamentally any software has to be ported, i.e. specifically adapted, to any kind of hardware it is supposed to be executed on. The level of abstraction that has been kept in mind while programming that software in the first place dictates the necessary effort.
The relevant term is of the porting target is computer architecture; it comprises the instruction set(s) and the microarchitecture(s) of the processor(s), at least of the CPU. The target also comprises the "system design" of the entire system, be it a supercomputer, a desktop computer or some SoC, e.g. in case some unique bus is being used. In former times, the memory controller was part of the chipset on the motherboard and not on the CPU-die.
Although the support of a specific instruction set is the task of the compiler, the software must be written with a certain level of abstraction in mind to make this portability possible. Any code written in Assembly language will be specific to the instruction set.
The support of a specific microarchitecture includes optimizations for the CPU cache hierarchy, the TLB, etc.

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

- Wikipedia: https://en.wikipedia.org/wiki/List_of_Linux-supported_computer_architectures