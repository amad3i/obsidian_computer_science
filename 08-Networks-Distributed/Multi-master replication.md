---
title: "Multi-master replication"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Multi-master_replication"
wikipedia_categories: ["Distributed computing architecture", "Identity management"]
related: ["[[Access control]]", "[[Aerospike (database)]]", "[[Aggregate Level Simulation Protocol]]", "[[Altibase]]", "[[Amoeba (operating system)]]", "[[Andrew Project]]", "[[Apache Accumulo]]", "[[Apache CouchDB]]", "[[Apache Samza]]", "[[Apache Storm]]"]
---

# Multi-master replication

Multi-master replication is a method of database replication which allows data to be stored by a group of computers, and updated by any member of the group. All members are responsive to client data queries. The multi-master replication system is responsible for propagating the data modifications made by each member to the rest of the group and resolving any conflicts that might arise between concurrent changes made by different members.
Multi-master replication can be contrasted with master-slave replication, in which a single member of the group is designated as the "master" for a given piece of data and is the only node allowed to modify that data item. Other members wishing to modify the data item must first contact the master node. Allowing only a single master makes it easier to achieve consistency among the members of the group, but is less flexible than multi-master replication.
Multi-master replication can also be contrasted with failover clustering where passive replica servers are replicating the master data in order to prepare for takeover in the event that the master stops functioning. The master is the only server active for client interaction.
Often, communication and replication in Multi-master systems are handled via a type of Consensus algorithm, but can also be implemented via custom or proprietary algorithms specific to the software.
The primary purposes of multi-master replication are increased availability and faster server response time.

## Related

- [[Access control]]
- [[Aerospike (database)]]
- [[Aggregate Level Simulation Protocol]]
- [[Altibase]]
- [[Amoeba (operating system)]]
- [[Andrew Project]]
- [[Apache Accumulo]]
- [[Apache CouchDB]]
- [[Apache Samza]]
- [[Apache Storm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Multi-master_replication