---
title: "Dataspace"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Dataspace"
wikipedia_categories: ["Information systems", "Information technology management"]
related: ["[[Business informatics]]", "[[Digital firm]]", "[[European Research Center for Information Systems]]", "[[Executive information system]]", "[[Local information systems]]", "[[Master of Business Informatics]]", "[[Service integration and management]]", "[[Accounting information system]]", "[[ADMAR]]", "[[Algorithmic management]]"]
---

# Dataspace

A dataspace is an abstraction in data management that aims to overcome some of the problems encountered in a data integration system.  A dataspace is defined as a set of "participants", or data sources, and the relations between them: for example that dataset A is a duplicate of dataset B. It can contain all data sources of an organization regardless of their format, physical location, or data model. The data space then provides a unified interface to query data regardless of format, sometimes in a "best-effort" fashion, and ways to further integrate the data when necessary. It is very different than a traditional relational database, which requires that all data be in the same format. The aim of the concept is to reduce the effort required to set up a data integration system by relying on existing matching and mapping generation techniques, and to improve the system in "pay-as-you-go" fashion as it is used. Labor-intensive aspects of data integration are postponed until they are absolutely needed.
Traditionally, data integration and data exchange systems have aimed to offer many of the purported services of dataspace systems. Dataspaces can be viewed as a next step in the evolution of data integration architectures, but are distinct from current data integration systems because they require semantic integration before any services can be provided. Hence, although there is not a single schema to which all the data conforms and the data resides in a multitude of host systems, the data integration system knows the precise relationships between the terms used in each schema. As a result, significant up-front effort is required in order to set up a data integration system.
Dataspaces shift the emphasis to a data co-existence approach providing base functionality over all data sources, regardless of how integrated they are. For example, a DataSpace Support Platform (DSSP) can provide keyword search over all of its data sources, similar to that provided by existing desktop search systems. When more sophisticated operations are required, such as relational-style queries, data mining, or monitoring over certain sources, then additional effort can be applied to more closely integrate those sources in an incremental fashion. Similarly, in terms of traditional database guarantees, initially a dataspace system can only provide weaker guarantees of consistency and durability. As stronger guarantees are desired, more effort can be put into making agreements among the various owners of data sources, and opening up certain interfaces (e.g., for commit protocols).

## Related

- [[Business informatics]]
- [[Digital firm]]
- [[European Research Center for Information Systems]]
- [[Executive information system]]
- [[Local information systems]]
- [[Master of Business Informatics]]
- [[Service integration and management]]
- [[Accounting information system]]
- [[ADMAR]]
- [[Algorithmic management]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dataspace