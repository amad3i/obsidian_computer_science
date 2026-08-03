---
title: "Row (database)"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Row_(database)"
wikipedia_categories: ["Data modeling", "Database management systems", "Relational model"]
related: ["[[Candidate key]]", "[[Materialized view]]", "[[Armstrong's axioms]]", "[[Cardinality (data modeling)]]", "[[Codd's 12 rules]]", "[[Column (database)]]", "[[Data control language]]", "[[Data query language]]", "[[Database normalization]]", "[[Database object]]"]
---

# Row (database)

In a relational database, a row or "record" or "tuple", represents a single, implicitly structured data item in a table. A database table can be thought of as consisting of rows and columns. Each row in a table represents a set of related data, and every row in the table has the same structure.
For example, in a table that represents companies, each row might represent a single company. Columns might represent things like company name, address, etc. In a table that represents the association of employees with departments, each row would associate one employee with one department.
The implicit structure of a row, and the meaning of the data values in a row, requires that the row be understood as providing a succession of data values, one in each column of the table. The row is then interpreted as a relvar composed of a set of tuples, with each tuple consisting of the two items: the name of the relevant column and the value this row provides for that column.
Each column expects a data value of a particular type.
For example, one column might require a unique identifier, another might require text representing a person's name, another might require an integer representing hourly pay in dollars.

## Related

- [[Candidate key]]
- [[Materialized view]]
- [[Armstrong's axioms]]
- [[Cardinality (data modeling)]]
- [[Codd's 12 rules]]
- [[Column (database)]]
- [[Data control language]]
- [[Data query language]]
- [[Database normalization]]
- [[Database object]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Row_(database)