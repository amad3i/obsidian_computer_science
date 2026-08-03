---
title: "White pages schema"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/White_pages_schema"
wikipedia_categories: ["Data management", "Data modeling", "Identity management"]
related: ["[[Data architect]]", "[[Data dictionary]]", "[[Database normalization]]", "[[Database schema]]", "[[Golden record (informatics)]]", "[[Log trigger]]", "[[Novell Storage Manager]]", "[[Physical schema]]", "[[PureXML]]", "[[Single customer view]]"]
---

# White pages schema

A white pages schema is a data model, specifically a logical schema, for organizing the data contained in entries in a directory service, database, or application, such as an address book. In a white pages directory, each entry typically represents an individual person that makes use of network resources, such as by receiving email or having an account to log into a system.
In some environments, the schema may also include the representation of organizational divisions, roles, groups, and devices.  The term is derived from the white pages, the listing of individuals in a telephone directory, typically sorted by the individual's home location (e.g. city) and then by
their name.
While many telephone service providers have for decades published a list of their subscribers in a telephone directory, and similarly corporations published a list of their employees in an internal directory, it was not until the rise of electronic mail systems that a requirement for standards for the electronic exchange of subscriber information between different systems appeared.
A white pages schema typically defines, for each real-world object being represented:

what attributes of that object are to be represented in the entry for that object
what relationships of that object to other objects are to be represented
how is the entry to be named in a DIT
how an entry is to be located by a client searching for it
how similar entries are to be distinguished
how are entries to be ordered when displayed in a list
One of the earliest attempts to standardize a white pages schema for electronic mail use was in X.520 and X.521, part of the X.500 specifications,
that was derived from the addressing requirements of X.400 and defined a Directory Information Tree that mirrored the international telephone system, with entries representing residential and organizational subscribers.  This evolved into the Lightweight Directory Access Protocol standard schema in RFC 2256.  One of the most widely deployed white pages schemas used in LDAP
for representing individuals in an organizational context is inetOrgPerson, defined in RFC 2798, although versions of Active Directory require a different object class, User.  Many large organizations have
also defined their own white pages schemas for their employees or customers, as part of their Identity management architecture.  Converting between data bases and directories using different schemas is often the
function of a Metadirectory, and data interchange standards such as Common Indexing Protocol.
Some early directory deployments suffered due to poor design choices in their white pages schema, such as:

attributes used for naming purposes were non-unique in large environments (such as a person's common name)
attributes used for naming purposes were likely to change (such as surnames)
attributes were included which could lead to Identity theft, such as a Social security number
users were required during provisioning to choose attributes which are unique but still memorable to them
Numerous other proposed schemas exist, both as standalone definitions suitable for use with general purpose
directories, or as embedded into network protocols.
Examples of other generic white pages schemas include vCard, defined in RFC 2426, and FOAF.

## Related

- [[Data architect]]
- [[Data dictionary]]
- [[Database normalization]]
- [[Database schema]]
- [[Golden record (informatics)]]
- [[Log trigger]]
- [[Novell Storage Manager]]
- [[Physical schema]]
- [[PureXML]]
- [[Single customer view]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/White_pages_schema