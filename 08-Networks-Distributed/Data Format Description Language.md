---
title: "Data Format Description Language"
tags: ["cs", "networks-distributed", "intermediate"]
domain: Networks & Distributed
level: intermediate
source: "https://en.wikipedia.org/wiki/Data_Format_Description_Language"
wikipedia_categories: ["Data modeling languages", "Grid computing"]
related: ["[[QL]]", "[[Access Grid]]", "[[Altair Engineering]]", "[[Apache Pig]]", "[[CDDLM]]", "[[Cognition enhanced Natural language Information Analysis Method]]", "[[D-Grid]]", "[[DRMAA]]", "[[Dynamic infrastructure]]", "[[EAST-ADL]]"]
---

# Data Format Description Language

Data Format Description Language (DFDL, often pronounced daff-o-dil) is a modeling language for describing general text and binary data in a standard way. It was published as an Open Grid Forum Recommendation  in February 2021, and in April 2024 was published as an ISO standard. 
A DFDL model or schema allows any text or binary data to be read (or "parsed") from its native format and to be presented as an instance of an information set. (An information set is a logical representation of the data contents, independent of the physical format. For example, two records could be in different formats, because one has fixed-length fields and the other uses delimiters, but they could contain exactly the same data, and would both be represented by the same information set). The same DFDL schema also allows data to be taken from an instance of an information set and written out (or "serialized") to its native format.
DFDL is descriptive and not prescriptive. DFDL is not a data format, nor does it impose the use of any particular data format. Instead it provides a standard way of describing many different kinds of data formats. This approach has several advantages. It allows an application author to design an appropriate data representation according to their requirements while describing it in a standard way which can be shared, enabling multiple programs to directly interchange the data.
DFDL achieves this by building upon the facilities of W3C XML Schema 1.0. A subset of XML Schema is used, enough to enable the modeling of non-XML data. The motivations for this approach are to avoid inventing a completely new schema language, and to make it easy to convert general text and binary data, via a DFDL information set, into a corresponding XML document.
Educational material is available in the form of DFDL Tutorials, videos and several hands-on DFDL labs.

## Related

- [[QL]]
- [[Access Grid]]
- [[Altair Engineering]]
- [[Apache Pig]]
- [[CDDLM]]
- [[Cognition enhanced Natural language Information Analysis Method]]
- [[D-Grid]]
- [[DRMAA]]
- [[Dynamic infrastructure]]
- [[EAST-ADL]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Data_Format_Description_Language