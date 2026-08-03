---
title: "SQL/PSM"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/SQL/PSM"
wikipedia_categories: ["Data-centric programming languages", "Data management", "Programming languages created in 1996", "SQL"]
related: ["[[Commit (data management)]]", "[[JADE (programming language)]]", "[[PL-Perl]]", "[[Skyline operator]]", "[[SQL]]", "[[A+ (programming language)]]", "[[Abstraction (computer science)]]", "[[Address space]]", "[[ADO.NET]]", "[[Alpha (programming language)]]"]
---

# SQL/PSM

SQL/PSM (SQL/Persistent Stored Modules) is an ISO standard mainly defining an extension of SQL with a procedural language for use in stored procedures. Initially published in 1996 as an extension of SQL-92 (ISO/IEC 9075-4:1996, a version sometimes called PSM-96 or even SQL-92/PSM), SQL/PSM was later incorporated into the multi-part SQL:1999 standard, and has been part 4 of that standard since then, most recently in SQL:2023.  The SQL:1999 part 4 covered less than the original PSM-96 because the SQL statements for defining, managing, and invoking routines were actually incorporated into part 2 SQL/Foundation, leaving only the procedural language itself as SQL/PSM. The SQL/PSM facilities are still optional as far as the SQL standard is concerned; most of them are grouped in Features P001-P008.
SQL/PSM standardizes syntax and semantics for control flow, exception handling (called "condition handling" in SQL/PSM), local variables, assignment of expressions to variables and parameters, and (procedural) use of cursors. It also defines an information schema (metadata) for stored procedures.  SQL/PSM is one language in which methods for the SQL:1999 structured types can be defined.  The other is Java, via SQL/JRT.
SQL/PSM is derived, seemingly directly, from Oracle's PL/SQL.  Oracle developed PL/SQL and released it in 1991, basing the language on the US Department of Defense's Ada programming language. However, Oracle has maintained a distance from the standard in its documentation. IBM's SQL PL (used in DB2) and Mimer SQL's PSM were the first two products officially implementing SQL/PSM. It is commonly thought that these two languages, and perhaps also MySQL/MariaDB's procedural language, are closest to the SQL/PSM standard.

  However, a PostgreSQL addon implements SQL/PSM (alongside its other procedural languages like the PL/SQL-derived plpgsql), although it is not part of the core product.
RDF functionality in OpenLink Virtuoso was developed entirely through SQL/PSM, combined with custom datatypes (e.g., ANY for handling URI and Literal relation objects), sophisticated indexing, and flexible physical storage choices (column-wise or row-wise).

## Related

- [[Commit (data management)]]
- [[JADE (programming language)]]
- [[PL-Perl]]
- [[Skyline operator]]
- [[SQL]]
- [[A+ (programming language)]]
- [[Abstraction (computer science)]]
- [[Address space]]
- [[ADO.NET]]
- [[Alpha (programming language)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/SQL/PSM