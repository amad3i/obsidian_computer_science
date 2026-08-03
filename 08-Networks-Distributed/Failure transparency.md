---
title: "Failure transparency"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Failure_transparency"
wikipedia_categories: ["Distributed computing"]
related: ["[[ActivityPub]]", "[[AT Protocol]]", "[[Availability zone]]", "[[Botnet]]", "[[CAP theorem]]", "[[CockroachDB]]", "[[Collective operation]]", "[[Comparison of synchronous and asynchronous signalling]]", "[[Confidential Consortium Framework]]", "[[Consensus dynamics]]"]
---

# Failure transparency

In a distributed system, failure transparency refers to the extent to which errors and subsequent recoveries of hosts and services within the system are invisible to users and applications.
For example, if a server fails, but users are automatically redirected to another server and never notice the failure, the system is said to exhibit high failure transparency.
Failure transparency is one of the most difficult types of transparency to achieve since it is often difficult to determine whether a server has actually failed, or whether it is simply responding very slowly.  Additionally, it is generally impossible to achieve full failure transparency in a distributed system since networks are unreliable.
There is also usually a trade-off between achieving a high level of failure transparency and maintaining an adequate level of system performance.  For example, if a distributed system attempts to mask a transient server failure by having the client try to contact the failed server multiple times, performance of the system may be negatively affected.  In this case, it would have been preferable to have given up earlier and tried another server.

## Related

- [[ActivityPub]]
- [[AT Protocol]]
- [[Availability zone]]
- [[Botnet]]
- [[CAP theorem]]
- [[CockroachDB]]
- [[Collective operation]]
- [[Comparison of synchronous and asynchronous signalling]]
- [[Confidential Consortium Framework]]
- [[Consensus dynamics]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Failure_transparency