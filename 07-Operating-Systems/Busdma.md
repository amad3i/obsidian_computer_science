---
title: "Busdma"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Busdma"
wikipedia_categories: ["Application programming interfaces", "BSD software", "DragonFly BSD", "FreeBSD", "NetBSD", "OpenBSD", "Operating system APIs", "Operating system technology"]
related: ["[[Kqueue]]", "[[Sysctl]]", "[[ALTQ]]", "[[Pfsync]]", "[[Soft updates]]", "[[Vinum volume manager]]", "[[FreeBSD jail]]", "[[Vkernel]]", "[[Application binary interface]]", "[[Binary Application Markup Language]]"]
---

# Busdma

In computing, busdma, bus_dma and bus_space is a set of application programming interfaces designed to help make device drivers less dependent on platform-specific code, thereby allowing the host operating system to be more easily ported to new computer hardware.  This is accomplished by having abstractions for direct memory access (DMA) mapping across popular machine-independent computer buses like PCI, which are used on distinct architectures from IA-32 (NetBSD/i386) to DEC Alpha (NetBSD/alpha).  Additionally, some devices may come in multiple flavours supporting more than one bus, e.g., ISA, EISA, VESA Local Bus and PCI, still sharing the same core logic irrespective of the bus, and such device drivers would also benefit from this same abstraction.  Thus the rationale of busdma is to facilitate maximum code reuse across a wide range of platforms.
Circa 2006, bus and DMA abstractions made it possible for NetBSD to support 50 hardware platforms and 14 CPU architectures out of a single source tree, compared to the forking model used by Linux ports.
Originally implemented as the "bus_dma" APIs by the developers of the NetBSD operating system, busdma has been adopted by OpenBSD, FreeBSD and their derivatives; with FreeBSD incorporating it under a busdma umbrella (without an underscore). Both NetBSD and OpenBSD have additional "bus_space" APIs that have been amalgamated into the version of busdma incorporated into FreeBSD. DragonFly BSD developers are also slowly converting their drivers to use busdma.

## Related

- [[Kqueue]]
- [[Sysctl]]
- [[ALTQ]]
- [[Pfsync]]
- [[Soft updates]]
- [[Vinum volume manager]]
- [[FreeBSD jail]]
- [[Vkernel]]
- [[Application binary interface]]
- [[Binary Application Markup Language]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Busdma