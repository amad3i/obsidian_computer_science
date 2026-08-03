---
title: "Schema crosswalk"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Schema_crosswalk"
wikipedia_categories: ["Data management", "Knowledge representation", "Library cataloging and classification", "Metadata", "Technical communication"]
related: ["[[Data custodian]]", "[[Data steward]]", "[[Learning object metadata]]", "[[Universal Data Element Framework]]", "[[Asset Description Metadata Schema]]", "[[Author name disambiguation]]", "[[Controlled vocabulary]]", "[[Data dictionary]]", "[[AgMES]]", "[[Altitude3.Net]]"]
---

# Schema crosswalk

A schema crosswalk is a table that shows equivalent elements (or "fields") in more than one database schema. It maps the elements in one schema to the equivalent elements in another.
Crosswalk tables are often employed within or in parallel to enterprise systems, especially when multiple systems are interfaced or when the system includes legacy system data. In the context of Interfaces, they function as an internal extract, transform, load (ETL) mechanism.
For example, this is a metadata crosswalk from MARC standards to Dublin Core:

Crosswalks show people where to put the data from one scheme into a different scheme. They are often used by libraries, archives, museums, and other cultural institutions to translate data to or from MARC standards, Dublin Core, Text Encoding Initiative (TEI), and other metadata schemes. For example, an archive has a MARC record in its catalog describing a manuscript. Suppose the archive makes a digital copy of that manuscript and wants to display it on the web along with the information from the catalog. In that case, it will have to translate the data from the MARC catalog record into a different format, such as Metadata Object Description Schema, that is viewable on a webpage. Because MARC has various fields than MODS, decisions must be made about where to put the data into MODS. This type of "translating" from one format to another is often called "metadata mapping" or "field mapping," and is related to "data mapping", and "semantic mapping".
Crosswalks also have several technical capabilities. They help databases using different metadata schemes to share information. They help metadata harvesters create union catalogs. They enable search engines to search multiple databases simultaneously with a single query.

## Related

- [[Data custodian]]
- [[Data steward]]
- [[Learning object metadata]]
- [[Universal Data Element Framework]]
- [[Asset Description Metadata Schema]]
- [[Author name disambiguation]]
- [[Controlled vocabulary]]
- [[Data dictionary]]
- [[AgMES]]
- [[Altitude3.Net]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Schema_crosswalk