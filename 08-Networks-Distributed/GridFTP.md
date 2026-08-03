---
title: "GridFTP"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/GridFTP"
wikipedia_categories: ["File Transfer Protocol", "Grid computing", "Network file transfer protocols"]
related: ["[[Access Grid]]", "[[Altair Engineering]]", "[[CDDLM]]", "[[Cloud-Based Secure File Transfer]]", "[[D-Grid]]", "[[Data Format Description Language]]", "[[DRMAA]]", "[[Dynamic infrastructure]]", "[[EMBRACE]]", "[[File eXchange Protocol]]"]
---

# GridFTP

GridFTP is an extension of the File Transfer Protocol (FTP) for grid computing.  The protocol was defined within the GridFTP working group of the Open Grid Forum. There are multiple implementations of the protocol; the most widely used is that provided by the Globus Toolkit.
The aim of GridFTP is to provide a more reliable and high performance file transfer, for example to enable the transmission of very large files. GridFTP is used extensively within large science projects such as the Large Hadron Collider and by many supercomputer centers and other scientific facilities.
GridFTP also addresses the problem of incompatibility between storage and access systems.  Previously, each data provider would make their data available in their own specific way, providing a library of access functions.  This made it difficult to obtain data from multiple sources, requiring a different access method for each, and thus dividing the total available data into partitions.  GridFTP provides a uniform way of accessing the data, encompassing functions from all the different modes of access, building on and extending the universally accepted FTP standard.  FTP was chosen as a basis for it because of its widespread use, and because it has a well defined architecture for extensions to the protocol (which may be dynamically discovered).

## Related

- [[Access Grid]]
- [[Altair Engineering]]
- [[CDDLM]]
- [[Cloud-Based Secure File Transfer]]
- [[D-Grid]]
- [[Data Format Description Language]]
- [[DRMAA]]
- [[Dynamic infrastructure]]
- [[EMBRACE]]
- [[File eXchange Protocol]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/GridFTP