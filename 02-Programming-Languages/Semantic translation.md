---
title: "Semantic translation"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Semantic_translation"
wikipedia_categories: ["Data management", "Enterprise application integration", "Semantics"]
related: ["[[Semantic heterogeneity]]", "[[Semantic integration]]", "[[Abstraction (computer science)]]", "[[Address space]]", "[[ADO.NET]]", "[[Altitude3.Net]]", "[[ANSI 834 Enrollment Implementation Format]]", "[[Approximate inference]]", "[[Archive site]]", "[[Asset Description Metadata Schema]]"]
---

# Semantic translation

Semantic translation is the process of using semantic information to aid in the translation of data in one representation or data model to another representation or data model.  Semantic translation takes advantage of semantics that associate meaning with individual data elements in one dictionary to create an equivalent meaning in a second system.
An example of semantic translation is the conversion of XML data from one data model to a second data model using formal ontologies for each system such as the Web Ontology Language (OWL).  This is frequently required by intelligent agents that wish to perform searches on remote computer systems that use different data models to store their data elements.  The process of allowing a single user to search multiple systems with a single search request is also known as federated search.
Semantic translation should be differentiated from data mapping tools that do simple one-to-one translation of data from one system to another without actually associating meaning with each data element.
Semantic translation requires that data elements in the source and destination systems have "semantic mappings" to a central registry or registries of data elements. The simplest mapping is of course where there is equivalence.
There are three types of Semantic equivalence:

Class Equivalence - indicating that class or "concepts" are equivalent.  For example: "Person" is the same as "Individual"
Property Equivalence - indicating that two properties are equivalent.  For example: "PersonGivenName" is the same as "FirstName"
Instance Equivalence - indicating that two individual instances of objects are equivalent.  For example: "Dan Smith" is the same person as "Daniel Smith"
Semantic translation is very difficult if the terms in a particular data model do not have direct one-to-one mappings to data elements in a foreign data model. In that situation, an alternative approach must be used to find mappings from the original data to the foreign data elements.  This problem can be alleviated by centralized metadata registries that use the ISO-11179 standards such as the National Information Exchange Model (NIEM).

## Related

- [[Semantic heterogeneity]]
- [[Semantic integration]]
- [[Abstraction (computer science)]]
- [[Address space]]
- [[ADO.NET]]
- [[Altitude3.Net]]
- [[ANSI 834 Enrollment Implementation Format]]
- [[Approximate inference]]
- [[Archive site]]
- [[Asset Description Metadata Schema]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Semantic_translation