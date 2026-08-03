---
title: "Distributed object"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Distributed_object"
wikipedia_categories: ["Distributed computing architecture"]
related: ["[[Aerospike (database)]]", "[[Aggregate Level Simulation Protocol]]", "[[Altibase]]", "[[Amoeba (operating system)]]", "[[Andrew Project]]", "[[Apache Accumulo]]", "[[Apache CouchDB]]", "[[Apache Samza]]", "[[Apache Storm]]", "[[ArangoDB]]"]
---

# Distributed object

In distributed computing, distributed objects are objects (in the sense of object-oriented programming) that are distributed across different address spaces, either in different processes on the same computer, or even in multiple computers connected via a network, but which work together by sharing data and invoking methods. This often involves location transparency, where remote objects appear the same as local objects. The main method of distributed object communication is with remote method invocation, generally by message-passing: one object sends a message to another object in a remote machine or process to perform some task. The results are sent back to the calling object.
Distributed objects were popular in the late 1990s and early 2000s, but have since fallen out of favor.
The term may also generally refer to one of the extensions of the basic object concept used in the context of distributed computing, such as replicated objects or live distributed objects.

Replicated objects are groups of software components (replicas) that run a distributed multi-party protocol to achieve a high degree of consistency between their internal states, and that respond to requests in a coordinated manner. Referring to the group of replicas jointly as an object reflects the fact that interacting with any of them exposes the same externally visible state and behavior.
Live distributed objects (or simply live objects) generalize the replicated object concept to groups of replicas that might internally use any distributed protocol, perhaps resulting in only a weak consistency between their local states. Live distributed objects can also be defined as running instances of distributed multi-party protocols, viewed from the object-oriented perspective as entities that have a distinct identity, and that can encapsulate distributed state and behavior.
See also Internet protocol suite.

## Related

- [[Aerospike (database)]]
- [[Aggregate Level Simulation Protocol]]
- [[Altibase]]
- [[Amoeba (operating system)]]
- [[Andrew Project]]
- [[Apache Accumulo]]
- [[Apache CouchDB]]
- [[Apache Samza]]
- [[Apache Storm]]
- [[ArangoDB]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Distributed_object