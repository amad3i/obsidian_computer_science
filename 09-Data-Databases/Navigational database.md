---
title: "Navigational database"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Navigational_database"
wikipedia_categories: ["Data management", "Types of databases"]
related: ["[[Distributed database]]", "[[Document-oriented database]]", "[[Key–value database]]", "[[Operational database]]", "[[Very large database]]", "[[XLDB]]", "[[Abstraction (computer science)]]", "[[Address space]]", "[[ADO.NET]]", "[[Altitude3.Net]]"]
---

# Navigational database

A navigational database is a type of database in which records or objects are found primarily by following references from other objects. The term was popularized by the title of Charles Bachman's 1973 Turing Award paper, The Programmer as Navigator. This paper emphasized the fact that the new disk-based database systems allowed the programmer to choose arbitrary navigational routes following relationships from record to record, contrasting this with the constraints of earlier magnetic-tape and punched card systems where data access was strictly sequential.
One of the earliest navigational databases was Integrated Data Store (IDS), which was developed by Bachman for General Electric in the 1960s. IDS became the basis for the CODASYL database model in 1969.
Although Bachman described the concept of navigation in abstract terms, the idea of navigational access came to be associated strongly with the procedural design of the CODASYL Data Manipulation Language. Writing in 1982, for example, Tsichritzis and Lochovsky state that "The notion of currency is central to the concept of navigation." By the notion of currency, they refer to the idea that a program maintains (explicitly or implicitly) a current position in any sequence of records that it is processing, and that operations such as GET NEXT and GET PRIOR retrieve records relative to this current position, while also changing the current position to the record that is retrieved.
Navigational database programming thus came to be seen as intrinsically procedural; and moreover to depend on the maintenance of an implicit set of global variables (currency indicators) holding the current state. As such, the approach was seen as diametrically opposed to the declarative programming style used by the relational model. The declarative nature of relational languages such as SQL offered better programmer productivity and a higher level of data independence (that is, the ability of programs to continue working as the database structure evolves.) Navigational interfaces, as a result, were gradually eclipsed during the 1980s by declarative query languages.
During the 1990s it started becoming clear that for certain applications handling complex data (for example, spatial databases and engineering databases), the relational calculus had limitations. At that time, a reappraisal of the entire database market began, with several companies describing the new systems using the marketing term NoSQL. Many of these systems introduced data manipulation languages which, while far removed from the CODASYL DML with its currency indicators, could be understood as implementing Bachman's "navigational" vision. Some of these languages are procedural; others (such as XPath) are entirely declarative. Offshoots of the navigational concept, such as the graph database, found new uses in modern transaction processing workloads.

## Related

- [[Distributed database]]
- [[Document-oriented database]]
- [[Key–value database]]
- [[Operational database]]
- [[Very large database]]
- [[XLDB]]
- [[Abstraction (computer science)]]
- [[Address space]]
- [[ADO.NET]]
- [[Altitude3.Net]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Navigational_database