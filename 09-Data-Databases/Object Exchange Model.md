---
title: "Object Exchange Model"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Object_Exchange_Model"
wikipedia_categories: ["Database management systems", "Database software stubs"]
related: ["[[Composite index (database)]]", "[[Data hub]]", "[[System 2000 (software)]]", "[[ACID]]", "[[ANSI-SPARC Architecture]]", "[[Apache Kylin]]", "[[Armstrong's axioms]]", "[[Array DBMS]]", "[[AutoNumber]]", "[[Azure Data Explorer]]"]
---

# Object Exchange Model

The Object Exchange Model  (OEM) is a model for exchanging semi-structured data between object-oriented databases. It serves as the basic data model in numerous projects of the Stanford University Database Group, including Tsimmis, Lore, and C3. 
Slight variations of OEM have evolved across different Stanford projects. In Lore, labels are actually on parent-child "links" rather than objects. For example, if an OEM object has multiple parents, different parent objects may use different labels to identify that object. An atomic value encoding a person's name might be included in one complex object using the label "Author" and in another complex object using the label "Editor." In C3, additional attributes are required for each object to annotate the changes to the object that have occurred over time.

## Related

- [[Composite index (database)]]
- [[Data hub]]
- [[System 2000 (software)]]
- [[ACID]]
- [[ANSI-SPARC Architecture]]
- [[Apache Kylin]]
- [[Armstrong's axioms]]
- [[Array DBMS]]
- [[AutoNumber]]
- [[Azure Data Explorer]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Object_Exchange_Model