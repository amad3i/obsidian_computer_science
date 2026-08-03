---
title: "Data orientation"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Data_orientation"
wikipedia_categories: ["Database models"]
related: ["[[Array DBMS]]", "[[Component-oriented database]]", "[[Data integration]]", "[[Database model]]", "[[Entity–attribute–value model]]", "[[Flat-file database]]", "[[Graph database]]", "[[Network model]]", "[[Object database]]"]
---

# Data orientation

Data orientation is the representation of tabular data in a  linear memory model such as in-disk or in-memory. The two most common representations are column-oriented (columnar format) and row-oriented (row format).
The choice of data orientation is a trade-off and an architectural decision in databases, query engines, and numerical simulations. As a result of these tradeoffs, row-oriented formats are more commonly used in online transaction processing (OLTP) and column-oriented formats are more commonly used in online analytical processing (OLAP).
Examples of column-oriented formats include Apache ORC, Apache Parquet, Apache Arrow, formats used by BigQuery, Amazon Redshift and Snowflake. Predominant examples of row-oriented formats include CSV, formats used in most relational databases (Oracle, MySQL etc.), the in-memory format of Apache Spark, and Apache Avro.

## Related

- [[Array DBMS]]
- [[Component-oriented database]]
- [[Data integration]]
- [[Database model]]
- [[Entity–attribute–value model]]
- [[Flat-file database]]
- [[Graph database]]
- [[Network model]]
- [[Object database]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Data_orientation