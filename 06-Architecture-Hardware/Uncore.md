---
title: "Uncore"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Uncore"
wikipedia_categories: ["Microprocessors"]
related: ["[[European Processor Initiative]]", "[[Instruction set architecture]]", "[[Interconnect bottleneck]]", "[[Latency oriented processor architecture]]", "[[List of microprocessors]]", "[[List of Russian microprocessors]]", "[[Media-embedded processor]]", "[[Megahertz myth]]", "[[Microarchitecture]]", "[[Microprocessor]]"]
---

# Uncore

"Uncore" is a term used by Intel to describe the functions of a microprocessor that are not in the core, but which must be closely connected to the core to achieve high performance. It was introduced with the Nehalem microarchitecture. It has been called "system agent" since the release of the Sandy Bridge microarchitecture.
The Uncore/SA handles the functionalities traditionally assigned to the northbridge: QPI controllers, L3 cache, snoop agent pipeline, on-die memory controller, on-die PCI Express Root Complex, and Thunderbolt controller. Integration of these functions into the core makes them physically closer, thereby reducing their access latency. In contrast, the "core" (processor) component consists of the control unit, ALU, FPU, and L1 and L2 caches. Other bus controllers such as SPI and LPC are part of the chipset (Platform Controller Hub), the equivalent of the southbridge. Further integration has since eliminated the PCH from the motherboard for a system-in-package design on mobile SKUs.

## Related

- [[European Processor Initiative]]
- [[Instruction set architecture]]
- [[Interconnect bottleneck]]
- [[Latency oriented processor architecture]]
- [[List of microprocessors]]
- [[List of Russian microprocessors]]
- [[Media-embedded processor]]
- [[Megahertz myth]]
- [[Microarchitecture]]
- [[Microprocessor]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Uncore