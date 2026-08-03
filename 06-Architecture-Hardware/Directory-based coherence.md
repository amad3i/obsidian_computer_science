---
title: "Directory-based coherence"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Directory-based_coherence"
wikipedia_categories: ["Computer architecture"]
related: ["[[Abstraction layer]]", "[[Address space]]", "[[Addressing mode]]", "[[Aperture (computer memory)]]", "[[Approximate computing]]", "[[Arithmetic logic unit]]", "[[Autonomous decentralized system]]", "[[Berkeley IRAM project]]", "[[Branch queue]]", "[[Bridging model]]"]
---

# Directory-based coherence

Directory-based coherence is a mechanism to handle cache coherence problem in distributed shared memory (DSM) a.k.a. non-uniform memory access (NUMA). Another popular way is to use a special type of computer bus between all the nodes as a "shared bus" (a.k.a. system bus). Directory-based coherence uses a special directory to serve instead of the shared bus in the bus-based coherence protocols. Both of these designs use the corresponding medium (i.e. directory or bus) as a tool to facilitate the communication between different nodes, and to guarantee that the coherence protocol is working properly along all the communicating nodes. In directory based cache coherence, this is done by using this directory to keep track of the status of all cache blocks, the status of each block includes in which cache coherence "state" that block is, and which nodes are sharing that block at that time, which can be used to eliminate the need to broadcast all the signals to all nodes, and only send it to the nodes that are interested in this single block.
Following are a few advantages and disadvantages of the directory based cache coherence protocol:

Scalability: This is one of the strongest motivations for going to directory based designs. Scalability is, in short, how good a specific system is in handling the growing amount of work that it is responsible to do. For this criterion, bus based systems cannot do well due to the limitation caused when having a shared bus that all nodes are using in the same time. For a relatively small number of nodes, bus systems can do well. However, while the number of nodes is growing, some problems may occur in this regard. Especially since only one node is allowed to use the bus at a time, which will significantly harm the performance of the overall system. On the other hand, using directory-based systems, there will be no such bottleneck to constrain the scalability of the system.
Simplicity: This is one of the points where the bus-system is superior. Since the bus structure itself can serve as an organizer for all the traffic that goes through the system, and ensure the atomicity of all the signals passed through, there will be no need to put more effort in ensuring atomicity and ordering between signals as the case in directory based systems, which leads to several overhead faced in the later system design when dealing with issues like consistency.
From the above discussion it follows that using bus based systems seems more attractive for relatively small systems. However, directory based systems become crucial when the system scales up and the number of nodes grows. So there is a kind of trade-off between the simplicity and the scalability when comparing between bus-based and directory-based cache coherence designs.

## Related

- [[Abstraction layer]]
- [[Address space]]
- [[Addressing mode]]
- [[Aperture (computer memory)]]
- [[Approximate computing]]
- [[Arithmetic logic unit]]
- [[Autonomous decentralized system]]
- [[Berkeley IRAM project]]
- [[Branch queue]]
- [[Bridging model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Directory-based_coherence