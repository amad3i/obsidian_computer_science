---
title: "Cdb (software)"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Cdb_(software)"
wikipedia_categories: ["Database management systems"]
related: ["[[ACID]]", "[[ANSI-SPARC Architecture]]", "[[Armstrong's axioms]]", "[[Array DBMS]]", "[[AutoNumber]]", "[[Azure Data Explorer]]", "[[Bidirectionalization]]", "[[Bigtable]]", "[[Block contention]]", "[[Candidate key]]"]
---

# Cdb (software)

cdb, short for "constant database", refers to both a library and data format created by Daniel J. Bernstein. cdb acts as an on-disk associative array, mapping keys to values, and allows multiple values to be stored for a single key. A constant database allows only two operations: creation and reading. Both operations are designed to be very fast and highly reliable. Since the database does not change while it is in use, multiple processes can access a single database without locking. Additionally, since all modifications create a replacement database, it can take advantage of UNIX filesystem semantics to provide a guarantee of reliability.
Record positions, key and value lengths, and hash values are 32-bit quantities and therefore must fit into 4 gigabytes. cdb is used by djbdns, fastforward, mess822, qmail and ucspi-tcp to provide highly efficient, reliable, and simple data access.

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

- Wikipedia: https://en.wikipedia.org/wiki/Cdb_(software)