---
title: "Document-oriented database"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Document-oriented_database"
wikipedia_categories: ["Data analysis", "Data management", "Database management systems", "Databases", "Document-oriented databases", "Types of databases"]
related: ["[[Key–value database]]", "[[Multi-model database]]", "[[Big data]]", "[[Concurrency control]]", "[[Couchbase Server]]", "[[Distributed database]]", "[[Imieliński–Lipski algebra]]", "[[NoSQL]]", "[[Commit (data management)]]", "[[Commitment ordering]]"]
---

# Document-oriented database

A document-oriented database, or document store, is a computer program and data storage system designed for storing, retrieving, and managing document-oriented information, also known as semi-structured data.
Document-oriented databases are one of the main categories of NoSQL databases, and the popularity of the term "document-oriented database" has grown alongside the adoption of NoSQL itself. XML databases are a subclass of document-oriented databases optimized for XML documents. Graph databases are similar in the way the store the raw data, but add another layer, the relationship, which allows them to link documents for rapid traversal.
Document-oriented databases are conceptually an extension of the key–value store, another type of NoSQL database. In key-value stores, data is treated as opaque by the database, whereas document-oriented systems exploit the internal structure of documents to extract metadata and optimize storage and queries. Although in practice the distinction can be minimal due to modern tooling, document stores are designed to provide a richer programming experience with modern programming techniques.
Document databases differ significantly from traditional relational databases (RDBs). Relational databases store data in predefined tables, often requiring an object to be split across multiple tables. In contrast, document databases store all information for a given object in a single document, with each document potentially having a unique structure. This design eliminates the need for object-relational mapping when loading data into the database.

## Related

- [[Key–value database]]
- [[Multi-model database]]
- [[Big data]]
- [[Concurrency control]]
- [[Couchbase Server]]
- [[Distributed database]]
- [[Imieliński–Lipski algebra]]
- [[NoSQL]]
- [[Commit (data management)]]
- [[Commitment ordering]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Document-oriented_database