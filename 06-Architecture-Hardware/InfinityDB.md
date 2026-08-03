---
title: "InfinityDB"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/InfinityDB"
wikipedia_categories: ["Cross-platform software", "Embedded databases", "Embedded systems", "Proprietary database management systems", "Structured storage"]
related: ["[[DuckDB]]", "[[4th Dimension (software)]]", "[[Apache CouchDB]]", "[[Couchbase Server]]", "[[FileMaker]]", "[[IBM Db2]]", "[[Lua]]", "[[Mimer SQL]]", "[[MonetDB]]", "[[TimesTen]]"]
---

# InfinityDB

InfinityDB is an all-Java embedded database engine and client/server DBMS with an extended java.util.concurrent.ConcurrentNavigableMap interface (a subinterface of java.util.Map) that is deployed in handheld devices, on servers, on workstations, and in distributed settings. The design is based on a proprietary lockless, concurrent, B-tree architecture that enables client programmers to reach high levels of performance without risk of failures.
A new Client/Server version 5.0 is in alpha testing, wrapping the established embedded version to provide shared access via a secure, remote server.
In the embedded system, data is stored to and retrieved from a single embedded database file using the InfnityDB API that allows direct access to the variable length item spaces. Database client programmers can construct traditional relations as well as specialized models that directly satisfy the needs of the dependent application. There is no limit to the number of items, database size, or JVM size, so InfinityDB can function in both the smallest environment that provides random access storage and can be scaled to large settings. Traditional relations and specialized models can be directed to the same database file. InfinityDB can be optimized for standard relations as well as all other types of data, allowing client applications to perform at a minimum of one million operations per second on a virtual, 8-core system.
AirConcurrentMap, is an in-memory map that implements the Java ConcurrentMap interface, but internally it uses a multi-core design so that its performance and memory make it the fastest Java Map when ordering is performed and it holds medium to large numbers of entries. AirConcurrentMap iteration is faster than any Java Map iterators, regardless of the specific map type.

## Related

- [[DuckDB]]
- [[4th Dimension (software)]]
- [[Apache CouchDB]]
- [[Couchbase Server]]
- [[FileMaker]]
- [[IBM Db2]]
- [[Lua]]
- [[Mimer SQL]]
- [[MonetDB]]
- [[TimesTen]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/InfinityDB