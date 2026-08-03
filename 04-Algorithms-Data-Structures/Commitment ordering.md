---
title: "Commitment ordering"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Commitment_ordering"
wikipedia_categories: ["Concurrency control", "Data management", "Databases", "Distributed algorithms", "Transaction processing"]
related: ["[[Concurrency control]]", "[[Database transaction schedule]]", "[[Distributed concurrency control]]", "[[Global serializability]]", "[[Locks with ordered sharing]]", "[[Big data]]", "[[Index locking]]", "[[Multi-model database]]", "[[Snapshot isolation]]", "[[Two-phase locking]]"]
---

# Commitment ordering

Commitment ordering (CO) is a class of interoperable serializability techniques in concurrency control of databases, transaction processing, and related applications. It allows optimistic (non-blocking) implementations. With the proliferation of multi-core processors, CO has also been increasingly utilized in concurrent programming, transactional memory, and software transactional memory (STM) to achieve serializability optimistically. CO is also the name of the resulting transaction schedule (history) property, defined in 1988 with the name dynamic atomicity. In a CO compliant schedule, the chronological order of commitment events of transactions is compatible with the precedence order of the respective transactions. CO is a broad special case of conflict serializability and effective means (reliable, high-performance, distributed, and scalable) to achieve global serializability (modular serializability) across any collection of database systems that possibly use different concurrency control mechanisms (CO also makes each system serializability compliant, if not already).
Each not-CO-compliant database system is augmented with a CO component (the commitment order coordinator—COCO) which orders the commitment events for CO compliance, with neither data-access nor any other transaction operation interference. As such, CO provides a low overhead, general solution for global serializability (and distributed serializability), instrumental for global concurrency control (and distributed concurrency control) of multi-database systems and other transactional objects, possibly highly distributed (e.g., within cloud computing, grid computing, and networks of smartphones). An atomic commitment protocol (ACP; of any type) is a fundamental part of the solution, utilized to break global cycles in the conflict (precedence, serializability) graph. CO is the most general property (a necessary condition) that guarantees global serializability, if the database systems involved do not share concurrency control information beyond atomic commitment protocol (unmodified) messages and have no knowledge of whether transactions are global or local (the database systems are autonomous). Thus CO (with its variants) is the only general technique that does not require the typically costly distribution of local concurrency control information (e.g., local precedence relations, locks, timestamps, or tickets). It generalizes the popular strong strict two-phase locking (SS2PL) property, which in conjunction with the two-phase commit protocol (2PC), is the de facto standard to achieve global serializability across (SS2PL based) database systems. As a result, CO compliant database systems (with any different concurrency control types) can transparently join such SS2PL based solutions for global serializability.
In addition, locking based global deadlocks are resolved automatically in a CO based multi-database environment, a vital side-benefit (including the special case of a completely SS2PL based environment; a previously unnoticed fact for SS2PL).
Furthermore, strict commitment ordering (SCO; Raz 1991c), the intersection of Strictness and CO, provides better performance (shorter average transaction completion time and resulting in better transaction throughput) than SS2PL whenever read-write conflicts are present (identical blocking behavior for write-read and write-write conflicts; comparable locking overhead). The advantage of SCO is especially during lock contention. Strictness allows both SS2PL and SCO to use the same effective database recovery mechanisms.
Two major generalizing variants of CO exist, extended CO (ECO; Raz 1993a) and multi-version CO (MVCO; Raz 1993b). They also provide global serializability without local concurrency control information distribution, can be combined with any relevant concurrency control, and allow optimistic (non-blocking) implementations. Both use additional information for relaxing CO constraints and achieving better concurrency and performance. Vote ordering (VO or Generalized CO (GCO); Raz 2009) is a container schedule set (property) and technique for CO and all its variants. Local VO is necessary for guaranteeing global serializability if the atomic commitment protocol (ACP) participants do not share concurrency control information (have the generalized autonomy property). CO and its variants inter-operate transparently, guaranteeing global serializability and automatic global deadlock resolution together in a mixed, heterogeneous environment with different variants.

## Related

- [[Concurrency control]]
- [[Database transaction schedule]]
- [[Distributed concurrency control]]
- [[Global serializability]]
- [[Locks with ordered sharing]]
- [[Big data]]
- [[Index locking]]
- [[Multi-model database]]
- [[Snapshot isolation]]
- [[Two-phase locking]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Commitment_ordering