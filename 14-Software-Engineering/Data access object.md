---
title: "Data access object"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Data_access_object"
wikipedia_categories: ["Architectural pattern (computer science)", "Software design patterns"]
related: ["[[Action–domain–responder]]", "[[Active record pattern]]", "[[Data mapper pattern]]", "[[Data transfer object]]", "[[Entity component system]]", "[[Front controller]]", "[[Identity map pattern]]", "[[Interceptor pattern]]", "[[Inversion of control]]", "[[JavaBeans]]"]
---

# Data access object

In software, a data access object (DAO) is a pattern that provides an abstract interface to some type of database or other persistence mechanism. By mapping application calls to the persistence layer, the DAO provides data operations without exposing database details. This isolation supports the single responsibility principle. It separates the data access the application needs, in terms of domain-specific objects and data types (the DAO's public interface), from how these needs can be satisfied with a specific DBMS (the implementation of the DAO).
Although this design pattern is applicable to most programming languages, most software with persistence needs, and most databases, it is traditionally associated with Java EE applications and with relational databases (accessed via the JDBC API because of its origin in Sun Microsystems' best practice guidelines "Core J2EE Patterns".
This object can be found in the Data Access layer of the 3-Tier Architecture.
There are various ways in which this object can be implemented:

One DAO for each table.
One DAO for all the tables for a particular DBMS.
Where the SELECT query is limited only to its target table and cannot incorporate JOINS, UNIONS, subqueries and Common Table Expressions (CTEs)
Where the SELECT query can contain anything that the DBMS allows.

## Related

- [[Action–domain–responder]]
- [[Active record pattern]]
- [[Data mapper pattern]]
- [[Data transfer object]]
- [[Entity component system]]
- [[Front controller]]
- [[Identity map pattern]]
- [[Interceptor pattern]]
- [[Inversion of control]]
- [[JavaBeans]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Data_access_object