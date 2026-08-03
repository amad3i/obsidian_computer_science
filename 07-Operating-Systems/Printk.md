---
title: "Printk"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Printk"
wikipedia_categories: ["Linux kernel", "Operating system APIs"]
related: ["[[Access method]]", "[[BogoMips]]", "[[Boot folder]]", "[[Booting process of Linux]]", "[[Busdma]]", "[[Configuration Menu Language]]", "[[Copy Fail]]", "[[Cryptoloop]]", "[[Debugfs]]", "[[DESQview]]"]
---

# Printk

printk is a printf-like function of the Linux kernel interface for formatting and writing kernel log entries. Since the C standard library (which contains the ubiquitous printf-like functions) is not available in kernel mode, printk provides for general-purpose output in the kernel. Due to limitations of the kernel design, the function is often used to aid debugging kernel mode software.
printk can be called from anywhere in the kernel except during early stages of the boot process, before the system console is initialized. The alternative function early_printk is implemented on some architectures and is used identically to printk but during the early stages of the boot process.

## Related

- [[Access method]]
- [[BogoMips]]
- [[Boot folder]]
- [[Booting process of Linux]]
- [[Busdma]]
- [[Configuration Menu Language]]
- [[Copy Fail]]
- [[Cryptoloop]]
- [[Debugfs]]
- [[DESQview]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Printk