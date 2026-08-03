---
title: "Module SQL"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Module_SQL"
wikipedia_categories: ["Data modeling languages", "Database APIs", "Declarative programming languages", "Query languages", "SQL", "SQL data access"]
related: ["[[SQL]]", "[[SQL syntax]]", "[[SQLf]]", "[[QL]]", "[[Alpha (programming language)]]", "[[Embedded SQL]]", "[[List of SPARQL implementations]]", "[[SPARQL]]", "[[SQL-2003]]", "[[SQL-2011]]"]
---

# Module SQL

Module SQL is a method of combining the computing power of a programming language and the database manipulation capabilities of SQL. Module SQL statements are SQL statements written in an SQL client module, that can be called as routines from the host language program source code like a host language routine. An SQL standard Module Language file is compiled into calls to a SQL runtime library that interacts with the Database management system. This allows programmers to call SQL statements from applications written in regular programming languages.
Using Module Language is very straightforward: place all SQL code in a separate module, and define an interface between the module containing the SQL code and the host program.
Module SQL is closely related to Embedded SQL. "SQL client modules are self-contained collections of SQL statements. Unlike embedded SQL, in which the SQL statements are inserted into the host programming language, SQL client modules are separate from the host language. The host language contains calls that invoke the module, which in turn executes the SQL statements within that module."

## Related

- [[SQL]]
- [[SQL syntax]]
- [[SQLf]]
- [[QL]]
- [[Alpha (programming language)]]
- [[Embedded SQL]]
- [[List of SPARQL implementations]]
- [[SPARQL]]
- [[SQL-2003]]
- [[SQL-2011]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Module_SQL