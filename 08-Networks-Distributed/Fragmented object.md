---
title: "Fragmented object"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Fragmented_object"
wikipedia_categories: ["Distributed computing architecture"]
related: ["[[Aerospike (database)]]", "[[Aggregate Level Simulation Protocol]]", "[[Altibase]]", "[[Amoeba (operating system)]]", "[[Andrew Project]]", "[[Apache Accumulo]]", "[[Apache CouchDB]]", "[[Apache Samza]]", "[[Apache Storm]]", "[[ArangoDB]]"]
---

# Fragmented object

In computing, fragmented objects are truly distributed objects. It is a novel design principle extending the traditional concept of stub based distribution. 
In contrast to distributed objects, they are physically distributed and encapsulate the distribution in the object itself. Parts of the object - named fragments - may exist on different nodes and provide the object's interface. Each client accessing a fragmented object by its unique object identity presumes a local fragment. Fragmented objects may act like a RPC-based infrastructure or a (caching) smart proxy as well. Therefore, clients cannot distinguish between the access of a local object, a local stub or a local fragment. Full transparency is gained by the following characteristics of fragmented objects.

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

- Wikipedia: https://en.wikipedia.org/wiki/Fragmented_object