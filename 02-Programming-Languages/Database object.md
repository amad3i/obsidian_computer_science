---
title: "Database object"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Database_object"
wikipedia_categories: ["Data modeling", "Database management systems", "SQL"]
related: ["[[Data control language]]", "[[Data query language]]", "[[Foreign key]]", "[[Table (database)]]", "[[Armstrong's axioms]]", "[[Candidate key]]", "[[Column (database)]]", "[[Commit (data management)]]", "[[Cursor (databases)]]", "[[Data manipulation language]]"]
---

# Database object

A database object is a structure for storing, managing and presenting application- or user-specific data in a database. Depending on the database management system (DBMS), many different types of database objects can exist. The following is a list of the most common types of database objects found in most relational databases (RDBMS):

Tablespace, storage space for tables in a database
Tables, a set of values organized into rows and columns
Indexes, a data structure providing faster queries (at the expense of slower writing and storage to maintain the index structure)
Views, a virtual table that is made as it is queried
Synonyms, alternate names for a table, view, sequence or other object in a database
Stored procedures and user-defined functions
Triggers, procedures which are run automatically based on specific events
Constraints, a constraint on the domain of an attribute
User accounts, schemas and permissions
Database objects are permanent, which means that they remain in their form as long as they are not explicitly changed or deleted. Application- or user-specific database objects in relational databases are usually created with data definition language (DDL) commands, which in SQL for example can be CREATE, ALTER and DROP.
Rows or tuples from the database can represent objects in the sense of object-oriented programming, but are not considered database objects.

## Related

- [[Data control language]]
- [[Data query language]]
- [[Foreign key]]
- [[Table (database)]]
- [[Armstrong's axioms]]
- [[Candidate key]]
- [[Column (database)]]
- [[Commit (data management)]]
- [[Cursor (databases)]]
- [[Data manipulation language]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Database_object