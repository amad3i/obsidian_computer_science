---
title: "Physical schema"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Physical_schema"
wikipedia_categories: ["Data management", "Data modeling"]
related: ["[[Data architect]]", "[[Data dictionary]]", "[[Database normalization]]", "[[Database schema]]", "[[Golden record (informatics)]]", "[[Log trigger]]", "[[PureXML]]", "[[Single source of truth]]", "[[White pages schema]]", "[[XML database]]"]
---

# Physical schema

A physical data model (or database design) is a representation of a data design as implemented, or intended to be implemented, in a database management system. In the lifecycle of a project it typically derives from a logical data model, though it may be reverse-engineered from a given database implementation. A complete physical data model will include all the database artifacts required to create relationships between tables or to achieve performance goals, such as indexes, constraint definitions, linking tables, partitioned tables or clusters. Analysts can usually use a physical data model to calculate storage estimates; it may include specific storage allocation details for a given database system.
As of 2012 seven main databases dominate the commercial marketplace: Informix, Oracle, Postgres, SQL Server, Sybase, IBM Db2 and MySQL. Other RDBMS systems tend either to be legacy databases or used within academia such as universities or further education colleges. Physical data models for each implementation would differ significantly, not least due to underlying operating-system requirements that may sit underneath them. For example: SQL Server runs only on Microsoft Windows operating-systems (Starting with SQL Server 2017, SQL Server runs on Linux. It's the same SQL Server database engine, with many similar features and services regardless of your operating system), while Oracle and MySQL can run on Solaris, Linux and other UNIX-based operating-systems as well as on Windows. This means that the disk requirements, security requirements and many other aspects of a physical data model will be influenced by the RDBMS that a database administrator (or an organization) chooses to use.

## Related

- [[Data architect]]
- [[Data dictionary]]
- [[Database normalization]]
- [[Database schema]]
- [[Golden record (informatics)]]
- [[Log trigger]]
- [[PureXML]]
- [[Single source of truth]]
- [[White pages schema]]
- [[XML database]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Physical_schema