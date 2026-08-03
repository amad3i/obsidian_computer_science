---
title: "No-force"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/No-force"
wikipedia_categories: ["Database management systems"]
related: ["[[ACID]]", "[[ANSI-SPARC Architecture]]", "[[Armstrong's axioms]]", "[[Array DBMS]]", "[[AutoNumber]]", "[[Azure Data Explorer]]", "[[Bidirectionalization]]", "[[Bigtable]]", "[[Block contention]]", "[[Candidate key]]"]
---

# No-force

A no-force policy is used in transaction control in database theory. The term no-force refers to the disk pages related to the actual database object being modified.
With a no-force policy, when a transaction commits, the changes made to the actual objects are not "forced", that is, required to be written to disk in-place.
A record of the changes must still be preserved at commit time to ensure that the transaction is durable. This record is typically written to a sequential transaction log, so that the actual changes to the database objects as recorded on disk can be written at a later time.
For frequently changed objects, a no-force policy allows updates to be merged and so reduces the number of write operations to the on-disk database object. A no-force policy also reduces the seek time required for a commit by having mostly sequential write operations to the transaction log, rather than requiring the disk to seek to many distinct database objects during a commit.

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

- Wikipedia: https://en.wikipedia.org/wiki/No-force