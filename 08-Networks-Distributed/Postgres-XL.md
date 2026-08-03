---
title: "Postgres-XL"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Postgres-XL"
wikipedia_categories: ["Distributed data stores", "Free database management systems", "PostgreSQL", "Relational database management systems"]
related: ["[[Altibase]]", "[[Apache Accumulo]]", "[[CUBRID]]", "[[DuckDB]]", "[[Firebird (database server)]]", "[[H2 Database Engine]]", "[[HSQLDB]]", "[[Ingres (database)]]", "[[List of SQL software and tools]]", "[[MonetDB]]"]
---

# Postgres-XL

Postgres-XL was a distributed relational database management system (RDBMS) software based on PostgreSQL. It aims to provide feature parity with PostgreSQL while distributing the workload over a cluster. The name "Postgres-XL" stands for "eXtensible Lattice".
The last release of Postgres-XL was made in September 2018 and development ceased in October. The website has also gone offline.
Some of the ideas and “smaller scale” features of Postgres-XL (parallel query, partitioning, distribution mindset) have been absorbed later by PostgreSQL. The major “Postgres-XL style” features (full shared-nothing horizontal write scale, built-in GTM, transparent multi-node sharding across the cluster in core) are not for PostgreSQL design, and the Big Data technological ecosystems followed other directions: see Citus and pg_duckdb (or pg_mooncake).
Postgres-XL is based on Postgres-XC, an earlier distributed PostgreSQL system developed by NTT Data and EnterpriseDB. In 2012, the cloud database startup StormDB adopted Postgres-XC and developed some proprietary extensions and improvements to it. In 2013, StormDB was acquired by TransLattice, and the improved software was open-sourced under the name "Postgres-XL" in 2014. Since 2015, Postgres-XL development has also been supported by 2ndQuadrant.
Postgres-XL provides cluster-wide consistent transaction snapshots via a central Global Transaction Manager (GTM) node. It requires a fast interconnect between nodes, so Postgres-XL is not suited to geographically distributed clusters. Larger queries can be split and parallelized between multiple nodes. Individual database tables can be chosen to be fully replicated across the cluster (usually for smaller tables) or sharded between separate nodes (for write scalability).

## Related

- [[Altibase]]
- [[Apache Accumulo]]
- [[CUBRID]]
- [[DuckDB]]
- [[Firebird (database server)]]
- [[H2 Database Engine]]
- [[HSQLDB]]
- [[Ingres (database)]]
- [[List of SQL software and tools]]
- [[MonetDB]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Postgres-XL