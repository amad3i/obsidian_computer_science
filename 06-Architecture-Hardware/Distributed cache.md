---
title: "Distributed cache"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Distributed_cache"
wikipedia_categories: ["Cache (computing)", "Distributed computing"]
related: ["[[ActivityPub]]", "[[AT Protocol]]", "[[Availability zone]]", "[[Botnet]]", "[[Cache (computing)]]", "[[Cache hierarchy]]", "[[Cache pollution]]", "[[Cache stampede]]", "[[CAP theorem]]", "[[CockroachDB]]"]
---

# Distributed cache

In computing, a distributed cache is an extension of the traditional concept of cache used in a single locale. A distributed cache may span multiple servers so that it can grow in size and in transactional capacity. It is mainly used to store application data residing in database and web session data. The idea of distributed caching has become feasible now because main memory has become very cheap and network cards have become very fast, with 1 Gbit now standard everywhere and 10 Gbit gaining traction. Also, a distributed cache works well on lower cost machines usually employed for web servers as opposed to database servers which require expensive hardware.
An emerging internet architecture known as Information-centric networking (ICN) is one of the best examples of a distributed cache network. The ICN is a network level solution hence the existing distributed network cache management schemes are not well suited for ICN. In the supercomputer environment, distributed cache is typically implemented in the form of burst buffer. 
In distributed caching, each cache key is assigned to a specific shard (a.k.a. partition). There are different sharding strategies: 

Modulus sharding
Range-based sharding
Consistent hashing evenly distributes cache keys across shards, even if some of the shards crash or become unavailable.

## Related

- [[ActivityPub]]
- [[AT Protocol]]
- [[Availability zone]]
- [[Botnet]]
- [[Cache (computing)]]
- [[Cache hierarchy]]
- [[Cache pollution]]
- [[Cache stampede]]
- [[CAP theorem]]
- [[CockroachDB]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Distributed_cache