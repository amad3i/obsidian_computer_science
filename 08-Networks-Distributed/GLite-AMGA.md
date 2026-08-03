---
title: "GLite-AMGA"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/GLite-AMGA"
wikipedia_categories: ["Grid computing products", "Metadata", "Middleware"]
related: ["[[Advanced Resource Connector]]", "[[Base One Foundation Component Library]]", "[[European Middleware Initiative]]", "[[GLite]]", "[[ProActive]]", "[[Storage Resource Broker]]", "[[SynfiniWay]]", "[[Virtuoso Universal Server]]", "[[ActiveVOS]]", "[[Advanced Message Queuing Protocol]]"]
---

# GLite-AMGA

The ARDA Metadata Grid Application (AMGA) is a general purpose metadata catalogue and part of the European Middleware Initiative middleware distribution. It was originally developed by the EGEE project as part of its gLite middleware, when it became clear that many Grid applications needed metadata information on files and to organize a work-flow. AMGA is now developed and supported by the European Middleware Initiative.
AMGA as a metadata service allows users to attach metadata information to files stored on the Grid, where metadata can be any relationally organized data typically stored in a relational database system (RDBMS). In addition, the metadata in AMGA can also be stored independently of any associated files, which allows AMGA to be used as a general access tool to relational databases on the Grid. AMGA features a simple to learn metadata access language, which has been very useful for the adoption of AMGA in smaller Grid applications, as it considerably lowers the technical hurdle to make use of relational data. Access via SQL92 is also supported.
One of the main features of AMGA, and one unique to it, is the possibility to replicate metadata between different AMGA instances allowing the federation of metadata  (e.g. By the Health-e-child project), but also to increase the scalability and improve the access times on a globally deployed Grid (as done by the Wisdom project). Performance and efficiency of the access across WANs has been independently targeted by an access protocol optimised for the bulk transfer of metadata across WANs using data streaming.
Security on the Grid is a major concern, and AMGA features different authentication methods via (Grid-Proxy-) Certificates as well as very flexible accesses control mechanisms for individual data items based on ACLs. In particular these security features have made AMGA the de facto standard for metadata and relational database access on the Grid for biomedical applications. Prominent projects making use of AMGA in this field are Wisdom where AMGA was used in both their campaigns against Avian Flu and malaria, and the Health e-Child project.

## Related

- [[Advanced Resource Connector]]
- [[Base One Foundation Component Library]]
- [[European Middleware Initiative]]
- [[GLite]]
- [[ProActive]]
- [[Storage Resource Broker]]
- [[SynfiniWay]]
- [[Virtuoso Universal Server]]
- [[ActiveVOS]]
- [[Advanced Message Queuing Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/GLite-AMGA