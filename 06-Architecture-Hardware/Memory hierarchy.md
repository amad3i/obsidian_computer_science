---
title: "Memory hierarchy"
tags: ["cs", "architecture-hardware", "core"]
domain: Architecture & Hardware
level: core
source: "https://en.wikipedia.org/wiki/Memory_hierarchy"
wikipedia_categories: ["Computer architecture", "Computer data storage", "Hierarchy"]
related: ["[[Computer data storage]]", "[[Abstraction layer]]", "[[Address space]]", "[[Addressing mode]]", "[[Aperture (computer memory)]]", "[[Approximate computing]]", "[[Arithmetic logic unit]]", "[[Autonomous decentralized system]]", "[[Berkeley IRAM project]]", "[[Bounding volume hierarchy]]"]
---

# Memory hierarchy

In computer architecture, the memory hierarchy separates computer storage into a hierarchy based on response time. Since response time, complexity, and capacity are related, the levels may also be distinguished by their performance and controlling technologies. Memory hierarchy affects performance in computer architectural design, algorithm predictions, and lower level programming constructs involving locality of reference. 
Designing for high performance requires considering the restrictions of the memory hierarchy, i.e. the size and capabilities of each component. Each of the various components can be viewed as part of a hierarchy of memories (m1, m2, ..., mn) in which each member mi is typically smaller and faster than the next highest member mi+1 of the hierarchy. To limit waiting by higher levels, a lower level will respond by filling a buffer and then signaling for activating the transfer.
There are four major storage levels.

Internal – processor registers and cache.
Main – the system RAM and controller cards.
On-line mass storage – secondary storage.
Off-line bulk storage – tertiary and off-line storage.
This is a general memory hierarchy structuring. Many other structures are useful.  For example, a paging algorithm may be considered as a level for virtual memory when designing a computer architecture, and one can include a level of nearline storage between online and offline storage.

== Properties of the technologies in the memory hierarchy ==
Adding complexity slows the memory hierarchy.
CMOx memory technology stretches the flash space in the memory hierarchy
One of the main ways to increase system performance is minimising how far down the memory hierarchy one has to go to manipulate data.
Latency and bandwidth are two metrics associated with caches. Neither of them is uniform, but is specific to a particular component of the memory hierarchy.
Predicting where in the memory hierarchy the data resides is difficult.
The location in the memory hierarchy dictates the time required for the prefetch to occur.

== Examples ==

The number of levels in the memory hierarchy and the performance at each level has increased over time. The type of memory or storage components also change historically.

Some CPUs include additional levels of cache between L3 and memory. For example, the Haswell microarchitecture includes an L4 cache of 128 MB on mobile units.
The lower levels of the hierarchy – from mass storage downwards – are also known as tiered storage. The formal distinction between online, nearline, and offline storage is:

Online storage is immediately available for I/O.
Nearline storage is not immediately available, but can be made online quickly without human intervention.
Offline storage is not immediately available, and requires some human intervention to bring online.
For example, always-on spinning disks are online, while spinning disks that spin down, such as massive arrays of idle disk (MAID), are nearline. Removable media such as tape cartridges that can be automatically loaded, as in a tape library, are nearline, while cartridges that must be manually loaded are offline.

== Programming ==
Most modern CPUs are so fast that, for most program workloads, the bottleneck is the locality of reference of memory accesses and the efficiency of the caching and memory transfer between different levels of the hierarchy. As a result, the CPU spends much of its time idling, waiting for memory I/O to complete.  This is sometimes called the space cost, as a larger memory object is more likely to overflow a small and fast level and require use of a larger, slower level. The resulting load on memory use is known as pressure (respectively register pressure, cache pressure, and (main) memory pressure). Terms for data being missing from a higher level and needing to be fetched from a lower level are, respectively: register spilling (due to register pressure: register to cache), cache miss (cache to main memory), and (hard) page fault (real main memory to virtual memory, i.e. mass storage, commonly referred to as disk regardless of the actual mass storage technology used).
Modern programming languages mainly assume two levels of memory, main (working) memory and mass storage. The exception is the relatively low-level assembly language and in the inline assemblers of higher-level languages such as C where "prefetch" instructions can be used to preload the cache. Taking optimal advantage of the memory hierarchy requires the cooperation of programmers, hardware, and compilers (as well as underlying support from the operating system):

Programmers are responsible for moving data between disk and memory through file I/O.
Hardware is responsible for moving data between memory and caches.
Optimizing compilers are responsible for generating code that, when executed, will cause the hardware to use caches and registers efficiently.
Many programmers assume one level of memory.  This works fine until the application hits a performance wall.  At that point, the programmer needs to change the code's memory access patterns to that it works well with cache resources.  A classic illustration of the effect of locality and caching is in the form of changing the order of iterating a three-dimensional array. Computer Systems: A Programmer's Perspective is a classic textbook that deals with this aspect of systems programming.

=== Memory tiering ===
Memory tiering is the practice of dividing the main memory into several levels by their performance characteristics, and (in analogy to storage tiering) moving memory content between them. What appears to be the "main memory" (physical address space) can be made up of heterogeneous parts due to NUMA, CXL-attached memory (on PCIe slots), Optane DCPMMs, or memory found on other expansion hardware such as coprocessors and GPUs, hence the need for tiering. Swapping can also be considered a form of tiering.
Memory tiering is implemented on Linux as an extension to NUMA, where each memory provider has a CPU-less NUMA node with an appropriate "abstract distance" reflecting its performance. The existing scheme for migrating memory between NUMA nodes using "hotness" indicated by page faults is adapted to tiering by Huang Ying (Al Maruf's TPP scheme is not in Linux mainline). It also uses a weighted-interleave allocation policy.

== See also ==
Cache hierarchy
Use of spatial and temporal locality: hierarchical memory
Buffer vs. cache
Cache hierarchy in a modern processor
Memory wall
Computer memory
Hierarchical storage management
Cloud storage
Memory access pattern
Communication-avoiding algorithm

== References ==

## Related

- [[Computer data storage]]
- [[Abstraction layer]]
- [[Address space]]
- [[Addressing mode]]
- [[Aperture (computer memory)]]
- [[Approximate computing]]
- [[Arithmetic logic unit]]
- [[Autonomous decentralized system]]
- [[Berkeley IRAM project]]
- [[Bounding volume hierarchy]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Memory_hierarchy