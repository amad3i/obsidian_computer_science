---
title: "Collocation (operating systems)"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Collocation_(operating_systems)"
wikipedia_categories: []
related: []
---

# Collocation (operating systems)

Collocation is a technique used in operating system design to improve the performance of microkernel-based systems. It moves code that would normally be running as an application into the kernel's address space to reduce the delays in context switches and message passing between different parts of the system. Such systems have more in common with classic "monolithic" kernels, like Unix, in that the kernel runs as a single program, but internally they are still organized as a set of intercommunicating tasks.
Collocation was widely explored in the 1990s as a way to improve the performance of systems based on the Mach kernel, with MkLinux being one example of an operating system using this approach. While it was successful in terms of improving the performance of the Mach system, in overall terms it was still far less performant than a traditional system, like Linux, running on the same platform. During this same period, the ever-growing amount of main memory and great increases in hard drive performance greatly lowered the development complexity of large monolithic kernels.
Collocation is much less common today, with some formerly collocation-based systems moving to traditional monolithic systems, one example being macOS' XNU. Another new approach to solving the communications overhead is the unikernel.

## Related

*(no automatic links — see MOC)*

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Collocation_(operating_systems)