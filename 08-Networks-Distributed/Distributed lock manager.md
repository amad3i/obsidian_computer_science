---
title: "Distributed lock manager"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Distributed_lock_manager"
wikipedia_categories: ["Distributed computing architecture"]
related: ["[[Aerospike (database)]]", "[[Aggregate Level Simulation Protocol]]", "[[Altibase]]", "[[Amoeba (operating system)]]", "[[Andrew Project]]", "[[Apache Accumulo]]", "[[Apache CouchDB]]", "[[Apache Samza]]", "[[Apache Storm]]", "[[ArangoDB]]"]
---

# Distributed lock manager

A distributed lock manager (DLM) runs in every machine in a cluster, with an identical copy of a cluster-wide lock database. Operating systems use lock managers to organise and serialise the access to resources. In this way a DLM provides software applications which are distributed across a cluster on multiple machines with a means to synchronize their accesses to shared resources.
DLMs have been used as the foundation for several successful clustered file systems, in which the machines in a cluster can use each other's storage via a unified file system, with significant advantages for performance and availability. The main performance benefit comes from solving the problem of disk cache coherency between participating computers. The DLM is used not only for file locking but also for coordination of all disk access. VMScluster, the first clustering system to come into widespread use, relied on the OpenVMS DLM in just this way.

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

- Wikipedia: https://en.wikipedia.org/wiki/Distributed_lock_manager