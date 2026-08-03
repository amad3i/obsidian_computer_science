---
title: "Information schema"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Information_schema"
wikipedia_categories: ["American National Standards Institute standards", "Computer standards", "Database stubs", "Databases"]
related: ["[[Data store]]", "[[Database dump]]", "[[Halloween Problem]]", "[[Hekaton (database)]]", "[[Index locking]]", "[[Integrated test facility]]", "[[International Clinical Trials Registry Platform]]", "[[Load file]]", "[[Locks with ordered sharing]]", "[[Pseudocolumn]]"]
---

# Information schema

In relational databases, the information schema (information_schema) is an ANSI-standard set of read-only views that provide information about all of the tables, views, columns, and procedures in a database. It can be used as a source of the information that some databases make available through non-standard commands, such as:

the SHOW command of MySQL
the DESCRIBE command of Oracle's SQL*Plus
the \d command in psql (PostgreSQL's default command-line program).
 => SELECT count(table_name) FROM information_schema.tables;
  count 
 -------
     99
 (1 row)
 => SELECT column_name, data_type, column_default, is_nullable
       FROM information_schema.columns WHERE table_name='alpha';
  column_name | data_type | column_default | is_nullable 
 -------------+-----------+----------------+-------------
  foo         | integer   |                | YES
  bar         | character |                | YES
 (2 rows)
 => SELECT * FROM information_schema.information_schema_catalog_name;
  catalog_name 
 --------------
  johnd
 (1 row)

## Related

- [[Data store]]
- [[Database dump]]
- [[Halloween Problem]]
- [[Hekaton (database)]]
- [[Index locking]]
- [[Integrated test facility]]
- [[International Clinical Trials Registry Platform]]
- [[Load file]]
- [[Locks with ordered sharing]]
- [[Pseudocolumn]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Information_schema