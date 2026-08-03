---
title: "Embedded SQL"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Embedded_SQL"
wikipedia_categories: ["Data modeling languages", "Database APIs", "Declarative programming languages"]
related: ["[[Module SQL]]", "[[QL]]", "[[List of SPARQL implementations]]", "[[SPARQL]]", "[[SQL]]", "[[SQL syntax]]", "[[SQLf]]", "[[Alpha (programming language)]]", "[[Apache Pig]]", "[[ASCEND]]"]
---

# Embedded SQL

Embedded SQL is a method of combining the computing power of a programming language and the database manipulation capabilities of SQL. Embedded SQL statements are SQL statements written inline with the program source code, of the host language. The embedded SQL statements are parsed by an embedded SQL preprocessor and replaced by host-language calls to a code library. The output from the preprocessor is then compiled by the host compiler. This allows programmers to embed SQL statements in programs written in any number of languages such as C/C++, COBOL and Fortran. This differs from SQL-derived programming languages that don't go through discrete preprocessors, such as PL/SQL and T-SQL.
The SQL standards committee defined the embedded SQL standard in two steps: a formalism called Module Language was defined, then the embedded SQL standard was derived from Module Language. The SQL standard defines embedding of SQL as embedded SQL and the language in which SQL queries are embedded is referred to as the host language. A popular host language is C. Host language C and embedded SQL, for example, is called Pro*C in Oracle and Sybase database management systems, ESQL/C in Informix, and ECPG in the PostgreSQL database management system.
SQL may also be embedded in languages like PHP etc.
The SQL standard SQL:2023 is available through purchase and contains chapter 21 Embedded SQL and its syntax rules.

## Related

- [[Module SQL]]
- [[QL]]
- [[List of SPARQL implementations]]
- [[SPARQL]]
- [[SQL]]
- [[SQL syntax]]
- [[SQLf]]
- [[Alpha (programming language)]]
- [[Apache Pig]]
- [[ASCEND]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Embedded_SQL