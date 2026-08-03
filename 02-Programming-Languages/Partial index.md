---
title: "Partial index"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Partial_index"
wikipedia_categories: ["Database management systems", "PostgreSQL"]
related: ["[[QUEL query languages]]", "[[ACID]]", "[[ANSI-SPARC Architecture]]", "[[Armstrong's axioms]]", "[[Array DBMS]]", "[[AutoNumber]]", "[[Azure Data Explorer]]", "[[Bidirectionalization]]", "[[Bigtable]]", "[[Block contention]]"]
---

# Partial index

In databases, a partial index, also known as filtered index is an index which has some condition applied to it so that it includes a subset of rows in the table.
This allows the index to remain small, even though the table may be rather large, and have extreme selectivity.
Suppose you have a transaction table where entries start out with STATUS = 'A' (active), and then may pass through other statuses ('P' for pending, 'W' for "being worked on") before reaching a final status, 'F', at which point it is no longer likely to be processed again.
In PostgreSQL, a useful partial index might be defined as:

This index would not bother storing any of the millions of rows that have reached "final" status, 'F', and would allow queries looking for transactions that still "need work" to efficiently search via this index.
Similarly, a partial index can be used to index only those rows where a column is not null, which will be of benefit when the column usually is null.

This index would allow the following query to read only the updated tuples:

It is not necessary that the condition be the same as the index criterion; Stonebraker's paper below presents a number of examples with indexes similar to the following:

## Related

- [[QUEL query languages]]
- [[ACID]]
- [[ANSI-SPARC Architecture]]
- [[Armstrong's axioms]]
- [[Array DBMS]]
- [[AutoNumber]]
- [[Azure Data Explorer]]
- [[Bidirectionalization]]
- [[Bigtable]]
- [[Block contention]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Partial_index