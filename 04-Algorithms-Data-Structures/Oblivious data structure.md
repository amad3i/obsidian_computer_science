---
title: "Oblivious data structure"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Oblivious_data_structure"
wikipedia_categories: ["Data structures"]
related: ["[[Active data structure]]", "[[Block availability map]]", "[[Comparison of data structures]]", "[[Compressed data structure]]", "[[Control block]]", "[[Directed acyclic graph]]", "[[Dynamization]]", "[[Implicit data structure]]", "[[Interval union-split-find]]", "[[List of data structures]]"]
---

# Oblivious data structure

In computer science, an oblivious data structure is a data structure that gives no information about the sequence or pattern of the operations that have been applied except for the final result of the operations.
In most conditions, even if the data is encrypted, the access pattern can be achieved, and this pattern can leak some important information such as encryption keys. And in the outsourcing of cloud data, this leakage of access pattern is still very serious.  An access pattern is a specification of an access mode for every attribute of a relation schema. For example, the sequences of user read or write the data in the cloud are access patterns.
We say a machine is oblivious if the sequence in which it accesses is equivalent for any two inputs with the same running time. So the data access pattern is independent from the input.
Applications:

Cloud data outsourcing: When writing or reading data from a cloud server, oblivious data structures are useful. And modern databases rely on data structures heavily, so oblivious data structures come in handy.
Secure processor: Tamper-resilient secure processors are used for defense against physical attacks or the malicious intruders access the users’ computer platforms. The existing secure processors designed in academia and industry include AEGIS and Intel SGX. But the memory addresses are still transferred in the clear on the memory bus. So the research finds that this memory buses can give out the information about encryption keys. With the Oblivious data structure comes in practical, the secure processor can obfuscate memory access pattern in a provably secure manner.
Secure computation: Traditionally people used circuit-model to do the secure computation, but the model is not enough for the security when the amount of data is getting big. RAM-model secure computation was proposed as an alternative to the traditional circuit model, and oblivious data structure is used to prevent information access behavioral being stolen.

## Related

- [[Active data structure]]
- [[Block availability map]]
- [[Comparison of data structures]]
- [[Compressed data structure]]
- [[Control block]]
- [[Directed acyclic graph]]
- [[Dynamization]]
- [[Implicit data structure]]
- [[Interval union-split-find]]
- [[List of data structures]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Oblivious_data_structure