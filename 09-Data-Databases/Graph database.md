---
title: "Graph database"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Graph_database"
wikipedia_categories: ["Database models", "Graph databases"]
related: ["[[ArangoDB]]", "[[Array DBMS]]", "[[Component-oriented database]]", "[[Data integration]]", "[[Data orientation]]", "[[Database model]]", "[[Entity–attribute–value model]]", "[[Flat-file database]]", "[[GUN (graph database)]]", "[[JanusGraph]]"]
---

# Graph database

A graph database (GDB) is a database that uses graph structures for semantic queries with nodes, edges, and properties to represent and store data. A key concept of the system is the graph (or edge or relationship). The graph relates the data items in the store to a collection of nodes and edges, the edges representing the relationships between the nodes. The relationships allow data in the store to be linked together directly and, in many cases, retrieved with one operation. Graph databases hold the relationships between data as a priority. Querying relationships is fast because they are perpetually stored in the database. Relationships can be intuitively visualized using graph databases, making them useful for heavily inter-connected data.
Graph databases are commonly referred to as a NoSQL database. Graph databases are similar to 1970s network model databases in that both represent general graphs, but network-model databases operate at a lower level of abstraction and lack easy traversal over a chain of edges.
The underlying storage mechanism of graph databases can vary. Relationships are first-class citizens in a graph database and can be labeled, directed, and given properties. Some depend on a relational engine and store the graph data in a table (although a table is a logical element, therefore this approach imposes a level of abstraction between the graph database management system and physical storage devices). Others use a key–value store or document-oriented database for storage, making them inherently NoSQL structures.
As of 2021, no graph query language has been universally adopted in the same way as SQL was for relational databases. There is a wide variety of systems used, many of which are tightly tied to one product. Early standardization efforts led to multi-vendor query languages like Gremlin, SPARQL, and Cypher. In September 2019 a proposal for a project to create a new standard graph query language (ISO/IEC 39075 Information Technology — Database Languages — GQL) was approved by members of ISO/IEC Joint Technical Committee 1(ISO/IEC JTC 1). GQL is intended to be a declarative database query language, like SQL. In addition to having query language interfaces, some graph databases are accessed through application programming interfaces (APIs).
Graph databases differ from graph compute engines. Graph databases are technologies that are translations of the relational online transaction processing (OLTP) databases. On the other hand, graph compute engines are used in online analytical processing (OLAP) for bulk analysis. Graph databases attracted considerable attention in the 2000s, due to the successes of major technology corporations using proprietary graph databases, along with the introduction of open-source graph databases.
One study concluded that an RDBMS was "comparable" in performance to existing graph analysis engines at executing graph queries.

## Related

- [[ArangoDB]]
- [[Array DBMS]]
- [[Component-oriented database]]
- [[Data integration]]
- [[Data orientation]]
- [[Database model]]
- [[Entity–attribute–value model]]
- [[Flat-file database]]
- [[GUN (graph database)]]
- [[JanusGraph]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Graph_database