---
title: "Connection pool"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Connection_pool"
wikipedia_categories: ["Database management systems"]
related: ["[[ACID]]", "[[ANSI-SPARC Architecture]]", "[[Armstrong's axioms]]", "[[Array DBMS]]", "[[AutoNumber]]", "[[Azure Data Explorer]]", "[[Bidirectionalization]]", "[[Bigtable]]", "[[Block contention]]", "[[Candidate key]]"]
---

# Connection pool

In software engineering, a connection pool is a cache of reusable database connections managed by the client or middleware. It reduces the overhead of opening and closing connections, improving performance and scalability in database applications.
SQL databases typically use stateful, binary protocols that maintain session-specific information, such as transaction states and prepared statements, necessitating optimized connection pooling to minimize the overhead of repeatedly establishing connections. Conversely, many mainstream NoSQL databases, like Azure Cosmos DB and Amazon DynamoDB, utilize stateless, HTTP-based protocols that handle each request independently. This architecture often reduces the need for traditional connection pooling, though reusing established connections can still offer performance benefits in high-throughput scenarios by avoiding the overhead of connection creation.

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

- Wikipedia: https://en.wikipedia.org/wiki/Connection_pool