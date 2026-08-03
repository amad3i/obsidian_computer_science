---
title: "Atomicity (database systems)"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Atomicity_(database_systems)"
wikipedia_categories: ["Data management", "Transaction processing"]
related: ["[[Big data]]", "[[Big memory]]", "[[Commit (data management)]]", "[[Commitment ordering]]", "[[Concurrency control]]", "[[Consistency (database systems)]]", "[[Data preservation]]", "[[Database transaction schedule]]", "[[Distributed concurrency control]]", "[[Distributed transaction]]"]
---

# Atomicity (database systems)

In database systems, atomicity (; from Ancient Greek: ἄτομος, romanized: átomos, lit. 'undividable') is the property of a database transaction consisting of an indivisible and irreducible series of database operations such that either all occur, or none occur. It is one of the ACID transaction properties: Atomicity, Consistency, Isolation, Durability. 
A guarantee of atomicity prevents partial database updates from occurring, because they can cause greater problems than rejecting the whole series outright. As a consequence, an atomic transaction cannot be observed to be in progress by another database client: at one moment in time, it has not yet happened, and at the next it has already occurred in whole (or nothing happened if the transaction was cancelled in progress).
An example of transaction atomicity could be a digital monetary transfer from bank account A to account B. It consists of two operations, debiting the money from account A and crediting it to account B. Performing both of these operations inside of an atomic transaction ensures that the database remains in a consistent state, if either operation fails there will not be any unaccountable credits or debits affecting either account.
The same term is also used in the definition of First normal form in database systems, where it instead refers to the concept that the values for fields may not consist of multiple smaller values to be decomposed, such as a string into which multiple names, numbers, dates, or other types may be packed.

## Related

- [[Big data]]
- [[Big memory]]
- [[Commit (data management)]]
- [[Commitment ordering]]
- [[Concurrency control]]
- [[Consistency (database systems)]]
- [[Data preservation]]
- [[Database transaction schedule]]
- [[Distributed concurrency control]]
- [[Distributed transaction]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Atomicity_(database_systems)