---
title: "Metadata repository"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Metadata_repository"
wikipedia_categories: ["Data modeling", "Databases", "Metadata", "Metadata registry"]
related: ["[[Common data model]]", "[[Data dictionary]]", "[[Data redundancy]]", "[[Elasticity (data store)]]", "[[Foreign key]]", "[[ISO 2146]]", "[[Lossless join decomposition]]", "[[Materialized view]]", "[[Relvar]]", "[[Synonym (database)]]"]
---

# Metadata repository

A metadata repository is a database created to store metadata. Metadata is information about the structures that contain the actual data. Metadata is often said to be "data about data", but this is misleading. Data profiles are an example of actual "data about data". Metadata adds one layer of abstraction to this definition– it is data about the structures that contain data. Metadata may describe the structure of any data, of any subject, stored in any format.
A well-designed metadata repository typically contains data far beyond simple definitions of the various data structures. Typical repositories store dozens to hundreds of separate pieces of information about each data structure.
Comparing the metadata of a couple data items - one digital and one physical - clarify what metadata is:
First, digital: For data stored in a database one may have a table called "Patient" with many columns, each containing data which describes a different attribute of each patient. One of these columns may be named "Patient_Last_Name". What is some of the metadata about the column that contains the actual surnames of patients in the database? We have already used two items: the name of the column that contains the data (Patient_Last_Name) and the name of the table that contains the column (Patient). Other metadata might include the maximum length of last name that may be entered, whether or not last name is required (can we have a patient without Patient_Last_Name?), and whether the database converts any surnames entered in lower case to upper case. Metadata of a security nature may show the restrictions which limit who may view these names.
Second, physical: For data stored in a brick and mortar library, one have many volumes and may have various media, including books. Metadata about books would include ISBN, Binding_Type, Page_Count, Author, etc. Within Binding_Type, metadata would include possible bindings, material, etc.
This contextual information of business data include meaning and content, policies that govern, technical attributes, specifications that transform, and programs that manipulate.

## Related

- [[Common data model]]
- [[Data dictionary]]
- [[Data redundancy]]
- [[Elasticity (data store)]]
- [[Foreign key]]
- [[ISO 2146]]
- [[Lossless join decomposition]]
- [[Materialized view]]
- [[Relvar]]
- [[Synonym (database)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Metadata_repository