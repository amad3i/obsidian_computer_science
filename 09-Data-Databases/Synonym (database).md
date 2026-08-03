---
title: "Synonym (database)"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Synonym_(database)"
wikipedia_categories: ["Data modeling", "Database management systems", "Databases"]
related: ["[[Foreign key]]", "[[Materialized view]]", "[[Armstrong's axioms]]", "[[Candidate key]]", "[[Column (database)]]", "[[Common data model]]", "[[Composite index (database)]]", "[[Concurrency control]]", "[[Data control language]]", "[[Data masking]]"]
---

# Synonym (database)

In databases, a synonym is an alias or alternate name for a table, view, sequence, or other schema object. They are used mainly to make it intuitive for users to access database objects owned by other users. They also hide the underlying object's identity and make it harder for a malicious program or user to target the underlying object (security through obscurity). Because a synonym is just an alternate name for an object, it requires no storage other than its definition. When an application uses a synonym, the DBMS forwards the request to the synonym's underlying base object. By coding your programs to use synonyms instead of database object names, you insulate yourself from any changes in the name, ownership, or object locations, at the cost of adding another layer that also needs to be maintained. Users can also have different needs, for example some may wish to use a shorter name to refer to database objects they often query, which can be done with aliases without having to rename the underlying object and alter the code referring to it.
Synonyms are very powerful from the point of view of allowing users access to objects that do not lie within their schema. All synonyms have to be created explicitly with the CREATE SYNONYM command and the underlying objects can be located in the same database or in other databases that are connected by database links
There are two major uses of synonyms:

Object invisibility: Synonyms can be created to keep the original object hidden from the user.
Location invisibility: Synonyms can be created as aliases for tables and other objects that are not part of the local database.
When a table or a procedure is created, it is created in a particular schema, and other users can access it only by using that schema's name as a prefix to the object's name.  The way around for this is for the schema owner creates a synonym with the same name as the table name.

## Related

- [[Foreign key]]
- [[Materialized view]]
- [[Armstrong's axioms]]
- [[Candidate key]]
- [[Column (database)]]
- [[Common data model]]
- [[Composite index (database)]]
- [[Concurrency control]]
- [[Data control language]]
- [[Data masking]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Synonym_(database)