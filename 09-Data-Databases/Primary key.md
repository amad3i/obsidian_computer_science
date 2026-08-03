---
title: "Primary key"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Primary_key"
wikipedia_categories: ["Data modeling", "Database management systems"]
related: ["[[Armstrong's axioms]]", "[[Candidate key]]", "[[Column (database)]]", "[[Data control language]]", "[[Data query language]]", "[[Database normalization]]", "[[Database object]]", "[[Foreign key]]", "[[Materialized view]]", "[[Row (database)]]"]
---

# Primary key

In the relational model of databases, a primary key is a designated set of attributes (column(s)) that can reliably identify and distinguish between each individual record in a table. The database creator can choose an existing unique attribute or combination of attributes from the table (a natural key) to act as its primary key, or create a new attribute containing a unique ID that exists solely for this purpose (a surrogate key). 
Examples of natural keys that could be suitable primary keys include data that is already by definition unique to all items in the table such as a national identification number attribute for person records, or the combination of a timestamp attribute with a location attribute for event records.
More formally, a primary key is a specific choice of a minimal set of attributes that uniquely specify a tuple (row) in a relation (table). A primary key is a choice of a candidate key (a minimal superkey); any other candidate key is an alternate key.

## Related

- [[Armstrong's axioms]]
- [[Candidate key]]
- [[Column (database)]]
- [[Data control language]]
- [[Data query language]]
- [[Database normalization]]
- [[Database object]]
- [[Foreign key]]
- [[Materialized view]]
- [[Row (database)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Primary_key