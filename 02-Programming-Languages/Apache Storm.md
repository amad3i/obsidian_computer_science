---
title: "Apache Storm"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Apache_Storm"
wikipedia_categories: ["Apache Software Foundation projects", "Cloud applications", "Cloud infrastructure", "Distributed computing architecture", "Distributed stream processing", "Java (software platform)", "Parallel computing", "Software using the Apache license"]
related: ["[[Apache Samza]]", "[[Apache Accumulo]]", "[[Apache CouchDB]]", "[[Apache Spark]]", "[[Tuple space]]", "[[Apache Ant]]", "[[Apache Calcite]]", "[[Apache CarbonData]]", "[[Apache Drill]]", "[[Apache Giraph]]"]
---

# Apache Storm

Apache Storm is a distributed stream processing computation framework written predominantly in the Clojure programming language. Originally created by Nathan Marz and team at BackType, the project was open sourced after being acquired by Twitter. It uses custom created "spouts" and "bolts" to define information sources and manipulations to allow batch, distributed processing of streaming data. The initial release was on 17 September 2011.
A Storm application is designed as a "topology" in the shape of a directed acyclic graph (DAG) with spouts and bolts acting as the graph vertices. Edges on the graph are named streams and direct data from one node to another. Together, the topology acts as a data transformation pipeline. At a superficial level the general topology structure is similar to a MapReduce job, with the main difference being that data is processed in real time as opposed to in individual batches. Additionally, Storm topologies run indefinitely until killed, while a MapReduce job DAG must eventually end.
Storm became an Apache Top-Level Project in September 2014 and was previously in incubation since September 2013.

## Related

- [[Apache Samza]]
- [[Apache Accumulo]]
- [[Apache CouchDB]]
- [[Apache Spark]]
- [[Tuple space]]
- [[Apache Ant]]
- [[Apache Calcite]]
- [[Apache CarbonData]]
- [[Apache Drill]]
- [[Apache Giraph]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Apache_Storm