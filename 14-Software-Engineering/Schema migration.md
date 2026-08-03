---
title: "Schema migration"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/Schema_migration"
wikipedia_categories: ["Agile software development"]
related: ["[[Acceptance testing]]", "[[Adaptation (computer science)]]", "[[Adaptive software development]]", "[[Agile contracts]]", "[[Agile software development]]", "[[Agile testing]]", "[[Ayotle]]", "[[Azure DevOps Server]]", "[[Continuous configuration automation]]", "[[Continuous integration]]"]
---

# Schema migration

In software engineering, a schema migration (also database migration, database change management) refers to the management of version-controlled, incremental and sometimes reversible changes to relational database schemas. A schema migration is performed on a database whenever it is necessary to update or revert that database's schema to some newer or older version.
Migrations are performed programmatically by using a schema migration tool. When invoked with a specified desired schema version, the tool automates the successive application or reversal of an appropriate sequence of schema changes until it is brought to the desired state.
Most schema migration tools aim to minimize the impact of schema changes on any existing data in the database. Despite this, preservation of data in general is not guaranteed because schema changes such as the deletion of a database column can destroy data (i.e. all values stored under that column for all rows in that table are deleted). Instead, the tools help to preserve the meaning of the data or to reorganize existing data to meet new requirements. Since meaning of the data often cannot be encoded, the configuration of the tools usually needs manual intervention.

## Related

- [[Acceptance testing]]
- [[Adaptation (computer science)]]
- [[Adaptive software development]]
- [[Agile contracts]]
- [[Agile software development]]
- [[Agile testing]]
- [[Ayotle]]
- [[Azure DevOps Server]]
- [[Continuous configuration automation]]
- [[Continuous integration]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Schema_migration