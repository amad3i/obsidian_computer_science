---
title: "Luleå algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Luleå_algorithm"
wikipedia_categories: ["Internet architecture", "Luleå University of Technology", "Networking algorithms", "Routing algorithms", "Routing software"]
related: ["[[Backpressure routing]]", "[[6bone]]", "[[A- search algorithm]]", "[[Adaptive quality of service multi-hop routing]]", "[[Address pool]]", "[[AiScaler]]", "[[Any-source multicast]]", "[[Anycast]]", "[[Application-layer framing]]", "[[Application-Layer Protocol Negotiation]]"]
---

# Luleå algorithm

The Luleå algorithm of computer science, designed by Degermark et al. (1997), is a  technique for storing and searching internet routing tables efficiently. It is named after the Luleå University of Technology, the home institute/university of the technique's authors. The name of the algorithm does not appear in the original paper describing it, but was used in a message from Craig Partridge to the Internet Engineering Task Force describing that paper prior to its publication.
The key task to be performed in internet routing is to match a given IPv4 address (viewed as a sequence of 32 bits) to the longest prefix of the address for which routing information is available. This prefix matching problem may be solved by a trie, but trie structures use a significant amount of space (a node for each bit of each address) and searching them requires traversing a sequence of nodes with length proportional to the number of bits in the address. The Luleå algorithm shortcuts this process by storing only the nodes at three levels of the trie structure, rather than storing the entire trie.
Before building the Luleå trie, the routing table entries need to be preprocessed. Any bigger prefix that overlaps a smaller prefix must be repeatedly split into smaller prefixes, and only the split prefixes which does not overlap the smaller prefix is kept. It is also required that the prefix tree is complete. If there is no routing table entries for the entire address space, it must be completed by adding dummy entries, which only carries the information that no route is present for that range. This enables the simplified lookup in the Luleå trie (Degermark et al. (1997)). See also Sundström 2007 - Note that is a complete PhD thesis that includes a description of the original Luleå Algorithm and a 2x speedup of the Luleå Algorithm, as well as two Hybrid Tree LPM algorithms supporting both dynamic updates and IPv6 lookups.
The main advantage of the Luleå algorithm for the routing task is that it uses very little memory, averaging 4–5 bytes per entry for large routing tables. This small memory footprint often allows the entire data structure to fit into the routing processor's cache, speeding operations. However, it has the disadvantage that it cannot be modified easily: small changes to the routing table may require most or all of the data structure to be reconstructed.
A modern home-computer (PC) has enough hardware/memory to perform the algorithm.

## Related

- [[Backpressure routing]]
- [[6bone]]
- [[A- search algorithm]]
- [[Adaptive quality of service multi-hop routing]]
- [[Address pool]]
- [[AiScaler]]
- [[Any-source multicast]]
- [[Anycast]]
- [[Application-layer framing]]
- [[Application-Layer Protocol Negotiation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Luleå_algorithm