---
title: "Booting process of Linux"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Booting_process_of_Linux"
wikipedia_categories: ["Booting processes", "Linux", "Linux kernel"]
related: ["[[History of Linux]]", "[[BogoMips]]", "[[Boot folder]]", "[[Configuration Menu Language]]", "[[Copy Fail]]", "[[Cryptoloop]]", "[[Debugfs]]", "[[Dirty COW]]", "[[Dprobes]]", "[[Dracut (software)]]"]
---

# Booting process of Linux

The Linux booting process involves multiple stages and is in many ways similar to the BSD and other Unix-style boot processes, from which it is derived. Although the Linux booting process depends very much on the computer architecture, those architectures share similar stages and software components, including system startup, bootloader execution, loading and startup of a Linux kernel image, and execution of various startup scripts and daemons. Those are grouped into 4 steps: system startup, bootloader stage, kernel stage, and init process.
When a Linux system is powered up or reset, its processor will execute a specific firmware/program for system initialization, such as the power-on self-test, invoking the reset vector to start a program at a known address in flash/ROM (in embedded Linux devices), then load the bootloader into RAM for later execution. In IBM PC–compatible personal computers (PCs), this firmware/program is either a BIOS or a UEFI monitor, and is stored in the mainboard. In embedded Linux systems, this firmware/program is called boot ROM. After being loaded into RAM, the bootloader (also called first-stage bootloader or primary bootloader) will execute to load the second-stage bootloader (also called secondary bootloader). The second-stage bootloader will load the kernel image into memory, decompress and initialize it, and then pass control to this kernel image. The second-stage bootloader also performs several operations on the system such as system hardware check, mounting the root device, loading the necessary kernel modules, etc. Finally, the first user-space process (init process) starts, and other high-level system initializations are performed (which involve with startup scripts).
For each of these stages and components, there are different variations and approaches; for example, GRUB, systemd-boot, coreboot or Das U-Boot can be used as bootloaders (historical examples are LILO, SYSLINUX or Loadlin), while the startup scripts can be either traditional init-style, or the system configuration can be performed through modern alternatives such as systemd or runit.

## Related

- [[History of Linux]]
- [[BogoMips]]
- [[Boot folder]]
- [[Configuration Menu Language]]
- [[Copy Fail]]
- [[Cryptoloop]]
- [[Debugfs]]
- [[Dirty COW]]
- [[Dprobes]]
- [[Dracut (software)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Booting_process_of_Linux