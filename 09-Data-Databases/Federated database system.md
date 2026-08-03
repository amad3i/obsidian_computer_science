---
title: "Federated database system"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Federated_database_system"
wikipedia_categories: ["Database management systems"]
related: ["[[ACID]]", "[[ANSI-SPARC Architecture]]", "[[Armstrong's axioms]]", "[[Array DBMS]]", "[[AutoNumber]]", "[[Azure Data Explorer]]", "[[Bidirectionalization]]", "[[Bigtable]]", "[[Block contention]]", "[[Candidate key]]"]
---

# Federated database system

A federated database system (FDBS) is a type of meta-database management system (DBMS), which transparently maps multiple autonomous database systems into a single federated database. The constituent databases are interconnected via a computer network and may be geographically decentralized. Since the constituent database systems remain autonomous, a federated database system is a contrastable alternative to the (sometimes daunting) task of merging several disparate databases. A federated database, or virtual database, is a composite of all constituent databases in a federated database system.  There is no actual data integration in the constituent disparate databases as a result of data federation.
Through data abstraction, federated database systems can provide a uniform user interface, enabling users and clients to store and retrieve data from multiple noncontiguous databases with a single query—even if the constituent databases are heterogeneous. To this end, a federated database system must be able to decompose the query into subqueries for submission to the relevant constituent DBMSs, after which the system must composite the result sets of the subqueries. Because various database management systems employ different query languages, federated database systems can apply wrappers to the subqueries to translate them into the appropriate query languages.

## Related

- [[ACID]]
- [[ANSI-SPARC Architecture]]
- [[Armstrong's axioms]]
- [[Array DBMS]]
- [[AutoNumber]]
- [[Azure Data Explorer]]
- [[Bidirectionalization]]
- [[Bigtable]]
- [[Block contention]]
- [[Candidate key]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Federated_database_system