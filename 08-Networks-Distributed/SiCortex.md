---
title: "SiCortex"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/SiCortex"
wikipedia_categories: ["Cluster computing", "MIPS architecture", "Parallel computing", "Supercomputers"]
related: ["[[Computer cluster]]", "[[Supercomputer]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Beowulf cluster]]", "[[Bright Computing]]", "[[Cluster manager]]", "[[Connection Machine]]", "[[Diskless shared-root cluster]]", "[[Distributed R]]"]
---

# SiCortex

SiCortex was a supercomputer manufacturer founded in 2003 and headquartered in Clock Tower Place, 
Maynard, Massachusetts. On 27 May 2009, HPCwire reported that the company had shut down its operations, laid off most of its staff, and is seeking a buyer for its assets. The Register reported that Gerbsman Partners was hired to sell SiCortex's intellectual properties. While SiCortex had some sales, selling at least 75 prototype supercomputers to several large customers, the company had never produced an operating profit and ran out of venture capital. New funding could not be found.
The company built and marketed a family of clusters of between 12 and 972 compute nodes, connected in a Kautz graph. The clusters are the SC5832, SC648 and SC072. It was reported that the company has been working on the next generation of clusters since March 2009, but development ceased when operations were closed.
The SC5832 is a high-end model housed in a cabinet. It has 972 nodes, 5,832 cores and 972 to 7,776 GB of memory. It uses a diameter-6 Kautz graph for 2,916 links. The SC648 is a mid-range model housed in a standard 19-inch rack. Each rack may contain two systems. It has 108 nodes, 648 cores and 108 to 864 GB of memory. It uses a diameter-4 Kautz graph for 324 links. The SC072 is a desktop model for developing software.
Each node is system-on-chip (SoC), codenamed ICE9, consisting of six cores that implement the MIPS64 instruction set architecture (ISA). Each core has a 32 KB instruction cache and a 32 KB data cache. The six cores have their own 256 KB L2 cache, which can be accessed by other cores. The MIPS cores execute instructions in-order and have a six-stage pipeline. They can issue and execute two instructions per cycle for peak double-precision (64-bit) performance of 1 GFLOPS at 500 MHz. This was later increased to 1.4 GFLOPS when the clock frequency of the SoC was increased to 700 MHz when the SoC was fabricated in a 90 nm process. The SoC contains two DDR2 memory controllers, each controlling a single DIMM. Each node can have 1 to 8 GB of memory. The SoC also implements a 8x PCI Express controller. The cluster interconnect is implemented by a DMA engine fabric switch. Each cluster interconnect provides a maximum bandwidth of 2 GB/s.
Message passing, via MPI, is the presumptive programming model. SiCortex systems run a customized Linux distribution derived from Gentoo Linux.

## Related

- [[Computer cluster]]
- [[Supercomputer]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]
- [[Beowulf cluster]]
- [[Bright Computing]]
- [[Cluster manager]]
- [[Connection Machine]]
- [[Diskless shared-root cluster]]
- [[Distributed R]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/SiCortex