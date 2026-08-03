---
title: "Transaction time"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Transaction_time"
wikipedia_categories: ["Computer programming stubs", "Database management systems", "Transaction processing"]
related: ["[[ACID]]", "[[Commit (data management)]]", "[[Concurrency control]]", "[[In-database processing]]", "[[Multi-model database]]", "[[Online transaction processing]]", "[[Quorum (distributed computing)]]", "[[Rollback (data management)]]", "[[Savepoint]]", "[[Temporal database]]"]
---

# Transaction time

In temporal databases, transaction time is the time when some data has been loaded into a database. The time when a transaction is valid can be called the transaction time-period. It is a technical timeline controlled by a integration layer (for example a data warehouse). More formally, it is the point-in-time during which a fact stored in the database is considered to be true.
The period is an interval based on load times (called load datetime in data vault), also called inscription timestamp. Other names of the interval is assertion timeline), state timeline) or technical timeline. SQL:2011 has support for transaction time through so-called system-versioned tables. 
For many reasons, transaction time (when data arrives from a source system) is almost always different from valid time (when the event happened in the real world). For a data warehouse to unambiguously report what actually happened in the past it must be able to combine these two timelines. In bitemporal data models, valid-time and transaction time can be represented two-dimensionally in a Cartesian coordinate system. When data is delivered from the integration layer and is to be presented in a presentation layer (often in a dimensional model or wide table) it is often desirable to have the data on only one timeline.
In a database table, the transaction time is often represented as an interval allowing the system to "remove" entries by using two table-columns start_tt and end_tt. The time interval is closed [ at its lower bound and open ) at its upper bound. When the ending transaction time is unknown, it may be considered as until_changed. Academic researchers and some relational database management systems (RDBMS) have represented until_changed with the largest timestamp supported or the keyword forever. This convention is a technical workaround, and not technically precise.

## Related

- [[ACID]]
- [[Commit (data management)]]
- [[Concurrency control]]
- [[In-database processing]]
- [[Multi-model database]]
- [[Online transaction processing]]
- [[Quorum (distributed computing)]]
- [[Rollback (data management)]]
- [[Savepoint]]
- [[Temporal database]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Transaction_time