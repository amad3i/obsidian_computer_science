---
title: "Expression index"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Expression_index"
wikipedia_categories: ["Database management systems"]
related: ["[[ACID]]", "[[ANSI-SPARC Architecture]]", "[[Armstrong's axioms]]", "[[Array DBMS]]", "[[AutoNumber]]", "[[Azure Data Explorer]]", "[[Bidirectionalization]]", "[[Bigtable]]", "[[Block contention]]", "[[Candidate key]]"]
---

# Expression index

Within computing and computer science, an expression index, also known as a function based index, is a database index that is built on a generic expression, rather than one or more columns. This allows indexes to be defined for common query conditions that depend on data in a table, but are not actually stored in that table.
A common use for an expression index is to support case-insensitive searching or constraints. For example, if a web site wants to make user names case-insensitive, but still preserve the case as originally entered by the user, an index can be created on the lower-case representation of the user name:

CREATE INDEX users__last_name_lower ON users( lower( last_name ) );
That will create a unique index on "lower(last_name)". Any queries that search on "lower(last_name)" could then make use of that index:

SELECT user_id FROM users WHERE lower( last_name ) = lower( 'Smith' );

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

- Wikipedia: https://en.wikipedia.org/wiki/Expression_index