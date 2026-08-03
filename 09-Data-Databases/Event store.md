---
title: "Event store"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Event_store"
wikipedia_categories: ["Databases"]
related: ["[[Altibase]]", "[[Autocommit]]", "[[Big data]]", "[[Catalog server]]", "[[Central Equipment Identity Register]]", "[[ChromaDB]]", "[[Commitment ordering]]", "[[Common data model]]", "[[Composite index (database)]]", "[[Concurrency control]]"]
---

# Event store

An event store is a type of database optimized for storage of events.
Conceptually, an event store records only the events affecting an entity, dossier, or policy, and the state of the entity at any point in its history can be reconstructed by replaying its contributing events in sequential order. Events (and their corresponding data) are the only "real" facts that should be stored in the database. All other objects can be derived from these events, meaning they are instantiated in memory by runtime code as needed (e.g. for showing in a user interface). In theory, any object that aggregates over recorded event data is not stored in the database. Instead these objects are built 'on the fly', by traversing the event history. When the aggregated object instance is no longer needed, it can simply be discarded (released from memory).

## Related

- [[Altibase]]
- [[Autocommit]]
- [[Big data]]
- [[Catalog server]]
- [[Central Equipment Identity Register]]
- [[ChromaDB]]
- [[Commitment ordering]]
- [[Common data model]]
- [[Composite index (database)]]
- [[Concurrency control]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Event_store