---
title: "History of computer clusters"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/History_of_computer_clusters"
wikipedia_categories: ["Cluster computing", "Concurrent computing", "History of computing hardware", "Parallel computing"]
related: ["[[Computer cluster]]", "[[Supercomputer]]", "[[Aiyara cluster]]", "[[Alewife (multiprocessor)]]", "[[Beowulf cluster]]", "[[Cache coherence]]", "[[Cluster manager]]", "[[Diskless shared-root cluster]]", "[[Distributed R]]", "[[IBM Parallel Sysplex]]"]
---

# History of computer clusters

The history of computer clusters is best captured by a footnote in Greg Pfister's In Search of Clusters: "Virtually every press release from DEC mentioning clusters says 'DEC, who invented clusters...'. IBM did not invent them either. Customers invented clusters, as soon as they could not fit all their work on one computer, or needed a backup. The date of the first is unknown, but it would be surprising if it was not in the 1960s, or even late 1950s."
The formal engineering basis of cluster computing as a means of doing parallel work of any sort was arguably invented by Gene Amdahl of IBM, who in 1967 published what has come to be regarded as the seminal paper on parallel processing: Amdahl's Law. Amdahl's Law describes mathematically the speedup one can expect from parallelizing any given otherwise serially performed task on a parallel architecture. This article defined the engineering basis for both multiprocessor computing and cluster computing, where the primary differentiator is whether or not the interprocessor communications are supported "inside" the computer (on for example a customized internal communications bus or network) or "outside" the computer on a commodity network.
Consequently, the history of early computer clusters is more or less directly tied into the history of early networks, as one of the primary motivations for the development of a network was to link computing resources, creating a de facto computer cluster. Packet switching networks were conceptually invented by the RAND corporation in 1962. Using the concept of a packet switched network, the ARPANET project succeeded in creating in 1969 what was arguably the world's first commodity-network based computer cluster by linking four different computer centers (each of which was something of a "cluster" in its own right, but probably not a commodity cluster). The ARPANET project grew into the Internet—which can be thought of as "the mother of all computer clusters" (as the union of nearly all of the compute resources, including clusters, that happen to be connected). It also established the paradigm in use by all computer clusters in the world today—the use of packet-switched networks to perform interprocessor communications between processor (sets) located in otherwise disconnected frames.
The development of customer-built and research clusters proceeded hand in hand with that of both networks and the Unix operating system from the early 1970s, as both TCP/IP and the Xerox PARC project created and formalized protocols for network-based communications. The Hydra operating system was built for a cluster of DEC PDP-11 minicomputers called C.mmp at Carnegie Mellon University in 1971. However, it was not until circa 1983 that the protocols and tools for easily doing remote job distribution and file sharing were defined (largely within the context of BSD Unix, as implemented by Sun Microsystems) and hence became generally available commercially, along with a shared filesystem.
The first commercial clustering product was ARCnet, developed by Datapoint in 1977. ARCnet was not a commercial success and clustering per se did not really take off until Digital Equipment Corporation released their VAXcluster product in 1984 for the VAX/VMS operating system. The ARCnet and VAXcluster products not only supported parallel computing, but also shared file systems and peripheral devices. The idea was to provide the advantages of parallel processing, while maintaining data reliability and uniqueness. VAXcluster, now VMScluster, is still available on OpenVMS running on Alpha, Itanium and x86-64 systems.
Two other noteworthy early commercial clusters were the Tandem Himalaya (a circa 1994 high-availability product) and the IBM S/390 Parallel Sysplex (also circa 1994, primarily for business use).
No history of commodity computer clusters would be complete without noting the pivotal role played by the development of Parallel Virtual Machine (PVM) software in 1989. This open source software based on TCP/IP communications enabled the instant creation of a virtual supercomputer—a high performance compute cluster—made out of any TCP/IP connected systems. Free-form heterogeneous clusters built on top of this model rapidly achieved total throughput in FLOPS that greatly exceeded that available even with the most expensive "big iron" supercomputers. PVM and the advent of inexpensive networked PCs led, in 1993, to a NASA project to build supercomputers out of commodity clusters. In 1995 the Beowulf cluster—a cluster built on top of a commodity network for the specific purpose of "being a supercomputer" capable of performing tightly coupled parallel HPC computations—was invented, which spurred the independent development of grid computing as a named entity, although Grid-style clustering had been around at least as long as the Unix operating system and the Arpanet, whether or not it, or the clusters that used it, were named.

## Related

- [[Computer cluster]]
- [[Supercomputer]]
- [[Aiyara cluster]]
- [[Alewife (multiprocessor)]]
- [[Beowulf cluster]]
- [[Cache coherence]]
- [[Cluster manager]]
- [[Diskless shared-root cluster]]
- [[Distributed R]]
- [[IBM Parallel Sysplex]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/History_of_computer_clusters