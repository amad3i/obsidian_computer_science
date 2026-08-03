---
title: "Decision time"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Decision_time"
wikipedia_categories: ["Database management systems"]
related: ["[[ACID]]", "[[ANSI-SPARC Architecture]]", "[[Armstrong's axioms]]", "[[Array DBMS]]", "[[AutoNumber]]", "[[Azure Data Explorer]]", "[[Bidirectionalization]]", "[[Bigtable]]", "[[Block contention]]", "[[Candidate key]]"]
---

# Decision time

In temporal databases, decision time is the time when a decision was made about a fact stored in a database. It is used to keep a history of decisions about valid times.
In a database table, the start and end time of the decision time interval can be represented by adding two table columns. This interval is closed [ in the lower bound, and open at the upper bound ). When a decision has not been replaced, the end time of the decision is unknown, and it can thus be considered valid "until changed" or infinite (∞).
Valid time and decision time are ways of modeling data, and is not applicable for all types of data, and transaction time is hence the most used temporal functionality. The concept of decision time can for example be used in bitemporal databases (together with valid time instead of transaction time), or in tritemporal databases.

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

- Wikipedia: https://en.wikipedia.org/wiki/Decision_time