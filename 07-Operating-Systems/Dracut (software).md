---
title: "Dracut (software)"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Dracut_(software)"
wikipedia_categories: ["Linux kernel"]
related: ["[[BogoMips]]", "[[Boot folder]]", "[[Booting process of Linux]]", "[[Configuration Menu Language]]", "[[Copy Fail]]", "[[Cryptoloop]]", "[[Debugfs]]", "[[Dirty COW]]", "[[Dprobes]]", "[[Dynamic Kernel Module Support]]"]
---

# Dracut (software)

Dracut is a set of tools that provide enhanced functionality for automating the Linux boot process. The tool named dracut is used to create a Linux boot image (initramfs) by copying tools and files from an installed system and combining it with the Dracut framework.
The initramfs has essentially one purpose: locating and mounting the real root file system so that the boot process can transition to it. This functionality is dependent on device availability. Therefore, instead of having hard-coded scripts to determine device availability and suitability, Dracut's initramfs depends on the Linux device manager (udev) to create symbolic links to device nodes. When the root file system's device node appears, Dracut mounts it as the new root file system. This helps to minimize the time required in initramfs such that, for example, 5-second boots are possible.
Most of the initramfs generation functionality in Dracut is provided by generator modules that are sourced by the main dracut tool to install specific functionality into the initramfs. They live in the modules subdirectory, and use functionality provided by dracut-functions to do their work.

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
- [[Dynamic Kernel Module Support]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dracut_(software)