---
title: "Failure detector"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Failure_detector"
wikipedia_categories: ["Distributed computing", "Fault-tolerant computer systems"]
related: ["[[Availability zone]]", "[[SWIM Protocol]]", "[[ActivityPub]]", "[[AT Protocol]]", "[[Botnet]]", "[[Byzantine fault]]", "[[CAP theorem]]", "[[CockroachDB]]", "[[Collective operation]]", "[[Comparison of synchronous and asynchronous signalling]]"]
---

# Failure detector

In a distributed computing system, a failure detector is a computer application or a subsystem that is responsible for the detection of node failures or crashes. Failure detectors were first introduced in 1996 by Chandra and Toueg in their book Unreliable Failure Detectors for Reliable Distributed Systems. The book depicts the failure detector as a tool to improve consensus (the achievement of reliability) and atomic broadcast (the same sequence of messages) in the distributed system. In other words, failure detectors seek errors in the process, and the system will maintain a level of reliability. In practice, after failure detectors spot crashes, the system will ban the processes that are making mistakes to prevent any further serious crashes or errors.
In the 21st century, failure detectors are widely used in distributed computing systems to detect application errors, such as a software application stops functioning properly. As the distributed computing projects (see List of distributed computing projects) become more and more popular, the usage of the failure detects also becomes important and critical.

## Related

- [[Availability zone]]
- [[SWIM Protocol]]
- [[ActivityPub]]
- [[AT Protocol]]
- [[Botnet]]
- [[Byzantine fault]]
- [[CAP theorem]]
- [[CockroachDB]]
- [[Collective operation]]
- [[Comparison of synchronous and asynchronous signalling]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Failure_detector