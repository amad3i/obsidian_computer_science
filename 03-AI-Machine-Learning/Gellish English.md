---
title: "Gellish English"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Gellish_English"
wikipedia_categories: ["Controlled English", "Knowledge representation", "Online English dictionaries"]
related: ["[[Attempto Controlled English]]", "[[WordNet]]", "[[4E cognition]]", "[[Agent Communications Language]]", "[[Agentive logic]]", "[[AgMES]]", "[[Agricultural Information Management Standards]]", "[[AGROVOC]]", "[[Allen's interval algebra]]", "[[Arabic Ontology]]"]
---

# Gellish English

The Gellish English Dictionary-Taxonomy is an example of an open-source “smart” electronic dictionary, in which concepts are arranged in a subtype-supertype hierarchy, thus forming a taxonomy. The dictionary-taxonomy is machine readable. It is compliant with the guidelines of ISO 16354. In addition to being an English business-technical dictionary, it also defines the semantics of Gellish English, which is a computer-interpretable structured subset of the natural English language for data storage and data exchange. The dictionary-taxonomy differs from conventional dictionaries because of several additional capabilities. This means that it satisfies the following criteria:

It contains definitions per concept, each represented by a unique identifier (UID; a natural number), whereas ordinary dictionaries usually provide multiple different definitions of a single term, whereas it is unclear whether those definitions are alternative definitions of the same concept or whether they are definitions of different concepts. Thus a smart dictionary explicitly distinguishes homonyms (the same term for different concepts) and explicitly specifies which terms are used as true synonyms, including also abbreviations, codes, etc.
It is defined itself in the form of a Gellish Data Tables that form a Gellish Database.
It is completely arranged as a taxonomy, which is a subtype-supertype hierarchy of concepts. This means that each concept is defined as an explicit subtype of one or more supertype concepts by specialization relations. This enables inheritance of definitions, knowledge, and requirements. An example of some definitions and hierarchy is the following:

It includes also concepts with multi-term names. For example: line shaft centrifugal pump. Ordinary dictionaries will only define the separate terms, from which it cannot always be inferred what the multi-term means.
It defines kinds of relations, also called relation types or fact types, as being special kinds of concepts. Such kinds of facts do not appear in ordinary dictionaries, because they are word-based and do not recognize standard phrases. However, fact types represent semantic concepts that are used by everybody to make sentences. Because these relation types are standardized and unambiguously defined, Gellish English becomes computer interpretable. The relation types in the dictionary-taxonomy include kinds that are specific for the expression of facts that represent knowledge, requirements, definitions, and information about individual things. The relation types have names and synonyms that consist of standardized phrases. For example (for clarity, the UIDs are not shown):

The phrase "is a part of" is a standard phrase for composition relations that can be used to express facts that relate parts to wholes. The other standard phrase "can have as part a" is a phrase for a concept that can be used to express knowledge that a whole of a particular kind can have as a part a component of a particular kind. The "shall have as part a" relation is intended to be used to express requirements. All phrases have also inverse expressions, such as "has as part" and "can be a part of a," which denote the same concepts (relation types), but which require an inverse sequence of the related objects. The following table illustrates the use of these relation types in Gellish English expressions.

Note: All elements in the last two expression above (pump, can/shall have as part a, and bearing) are "names" of standard English concepts that are defined in the Gellish English Dictionary-Taxonomy or a proprietary extension, such as for "pump type A."

It includes explicit relations between concepts, using the above mentioned standardized relation types. Those relations express knowledge about the concepts. This means that the dictionary-taxonomy is also an ontology. If a user of an application system classifies an individual object by a concept in the dictionary-taxonomy, then a computer system can infer that the knowledge and requirements about the concept are applicable to that individual object, and it can make that information available to that user. This includes also the knowledge and requirements that are available about the supertypes of that concepts, because such knowledge and requirements are inherited by the subtype of those supertype concepts, conforming to the subtype-supertype hierarchy (the taxonomy).
It enables automatic translation and search in databases in other languages. This is possible because each concept is represented by a language-independent UID, whereas multiple terms (names) in various languages are allowed to denote the same concept. This makes it possible for facts that are expressed in one language to be automatically presented by a computer in any other language for which a smart dictionary is available. It also makes it possible to answer queries in one language using database systems that contain facts that are expressed in other languages and then present the results in the language in which the query was formulated.
It can be extended by private and proprietary concepts and terms. For example, company specific codes and proprietary knowledge can be added as required. Guidelines for the "proper definition of a concept" are provided in the documentation.
It is computer interpretable and system independent.
The Gellish English Dictionary-Taxonomy is available as a collection of standardized Gellish Data Tables. Each of those tables has the same standard column definitions. Thus the whole dictionary-taxonomy can be treated as if it were one table.
The Gellish English Dictionary is freely available under open-source conditions (through one of the open source licenses) via the SourceForge Web site. Further documentation is available on the Gellish official website.

## Related

- [[Attempto Controlled English]]
- [[WordNet]]
- [[4E cognition]]
- [[Agent Communications Language]]
- [[Agentive logic]]
- [[AgMES]]
- [[Agricultural Information Management Standards]]
- [[AGROVOC]]
- [[Allen's interval algebra]]
- [[Arabic Ontology]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Gellish_English