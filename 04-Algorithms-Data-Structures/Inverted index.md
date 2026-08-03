---
title: "Inverted index"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Inverted_index"
wikipedia_categories: ["Data management", "Database index techniques", "Search algorithms", "Substring indices"]
related: ["[[BitFunnel]]", "[[Bitmap index]]", "[[Hierarchical navigable small world]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[A- search algorithm]]", "[[Abstraction (computer science)]]", "[[Address space]]", "[[ADO.NET]]", "[[All nearest smaller values]]", "[[Alpha–beta pruning]]"]
---

# Inverted index

In information science, an inverted index (also referred to as a postings list, postings file, or inverted file) is a database index storing a mapping from content, such as words or numbers, to its locations in a table, or in a document or a set of documents (named in contrast to a forward index, which maps from documents to content). The purpose of an inverted index is to allow fast full-text searches, at a cost of increased processing when a document is added to the database. The inverted file may be the database file itself, rather than its index. It is the most popular data structure used in document retrieval systems, used on a large scale for example in search engines. Additionally, several significant general-purpose mainframe-based database management systems have used inverted list architectures, including ADABAS, DATACOM/DB, and Model 204.
There are two main variants of inverted indexes: A record-level inverted index (or inverted file index or just inverted file) contains a list of references to documents for each word. A word-level inverted index (or full inverted index or inverted list) additionally contains the positions of each word within a document. The latter form offers more functionality (like phrase searches), but needs more processing power and space to be created.

## Related

- [[BitFunnel]]
- [[Bitmap index]]
- [[Hierarchical navigable small world]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[A- search algorithm]]
- [[Abstraction (computer science)]]
- [[Address space]]
- [[ADO.NET]]
- [[All nearest smaller values]]
- [[Alpha–beta pruning]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Inverted_index