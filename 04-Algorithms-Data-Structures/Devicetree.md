---
title: "Devicetree"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Devicetree"
wikipedia_categories: ["ARM architecture", "Data structures by computing platform", "Embedded systems", "Firmware", "Operating system technology"]
related: ["[[Board support package]]", "[[Hardware abstraction]]", "[[Adesto Technologies]]", "[[ADvantage Framework]]", "[[ALTQ]]", "[[Anti-hijack system]]", "[[Apache Celix]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Assembly language]]"]
---

# Devicetree

In computing, a devicetree (also written device tree) is a data structure describing the hardware components of a particular computer so that the operating system's kernel can use and manage those components, including the CPU or CPUs, the memory, the buses and the integrated peripherals.
The device tree was derived from SPARC-based and PowerPC-based computers via the Open Firmware project. The current Devicetree specification
is targeted at smaller systems and embedded systems, but is still used with some server-class systems (for instance, those described by the Power Architecture Platform Reference).
Personal computers with the x86 architecture generally do not use device trees, relying instead on various auto configuration protocols (e.g. ACPI) to discover hardware. Systems which use device trees usually pass a static device tree (perhaps stored in EEPROM, or stored in NAND device like eUFS) to the operating system, but can also generate a device tree in the early stages of booting. As an example, Das U-Boot and kexec can pass a device tree when launching a new operating system. On systems with a boot loader that does not support device trees, a static device tree may be installed along with the operating system; the Linux kernel supports this approach.
The Devicetree specification is currently managed by a community named devicetree.org, which is associated with, among others, Linaro and Arm.

## Related

- [[Board support package]]
- [[Hardware abstraction]]
- [[Adesto Technologies]]
- [[ADvantage Framework]]
- [[ALTQ]]
- [[Anti-hijack system]]
- [[Apache Celix]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Assembly language]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Devicetree