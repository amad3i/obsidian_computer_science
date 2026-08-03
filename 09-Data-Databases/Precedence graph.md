---
title: "Precedence graph"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Precedence_graph"
wikipedia_categories: ["Database management systems"]
related: ["[[ACID]]", "[[ANSI-SPARC Architecture]]", "[[Armstrong's axioms]]", "[[Array DBMS]]", "[[AutoNumber]]", "[[Azure Data Explorer]]", "[[Bidirectionalization]]", "[[Bigtable]]", "[[Block contention]]", "[[Candidate key]]"]
---

# Precedence graph

A precedence graph, also named conflict graph and serializability graph, is used in the context of concurrency control in databases. It is the directed graph representing precedence of transactions in the schedule, as reflected by precedence of conflicting operations in the transactions. A schedule is conflict-serializable if and only if its precedence graph of committed transactions is acyclic.
The precedence graph for a schedule S contains:

A node for each committed transaction in S
An arc from Ti to Tj if an action of Ti precedes and conflicts with one of Tj's actions. That is the actions belong to different transactions, at least one of the actions is a write operation, and the actions access the same object (read or write).
Cycles of committed transactions can be prevented by aborting an undecided (neither committed, nor aborted) transaction on each cycle in the precedence graph of all the transactions, which can otherwise turn into a cycle of committed transactions (and a committed transaction cannot be aborted). One transaction aborted per cycle is both required and sufficient in number to break and eliminate the cycle (more aborts are possible, and can happen under some mechanisms, but are unnecessary for serializability). The probability of cycle generation is typically low, but, nevertheless, such a situation is carefully handled, typically with a considerable amount of overhead, since correctness is involved. Transactions aborted due to serializability violation prevention are restarted and executed again immediately.

## Related

- [[ACID]]
- [[ANSI-SPARC Architecture]]
- [[Armstrong's axioms]]
- [[Array DBMS]]
- [[AutoNumber]]
- [[Azure Data Explorer]]
- [[Bidirectionalization]]
- [[Bigtable]]
- [[Block contention]]
- [[Candidate key]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Precedence_graph