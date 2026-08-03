---
title: "Attempto Controlled English"
tags: ["cs", "programming-languages", "advanced"]
domain: Programming & Languages
level: advanced
source: "https://en.wikipedia.org/wiki/Attempto_Controlled_English"
wikipedia_categories: ["Controlled English", "Knowledge representation", "Knowledge representation languages", "Natural language parsing", "Natural language processing", "Proof assistants"]
related: ["[[Arabic Ontology]]", "[[ChatScript]]", "[[Document classification]]", "[[Gellish English]]", "[[Logic form]]", "[[Natural Language Toolkit]]", "[[NetMiner]]", "[[Rhetorical structure theory]]", "[[Syntactic parsing (computational linguistics)]]", "[[4E cognition]]"]
---

# Attempto Controlled English

Attempto Controlled English (ACE) is a controlled natural language, i.e. a subset of standard English with a restricted syntax and restricted semantics described by a small set of construction and interpretation rules. It has been under development at the University of Zurich since 1995. In 2013, ACE version 6.7 was announced.
ACE can serve as knowledge representation, specification, and query language, and is intended for professionals who want to use formal notations and formal methods, but may not be familiar with them. Though ACE appears perfectly natural—it can be read and understood by any speaker of English—it is in fact a formal language.
ACE and its related tools have been used in the fields of software specifications, theorem proving, proof assistants, text summaries, ontologies, rules, querying, medical documentation and planning.
Here are some simple examples:

Every woman is a human.
A woman is a human.
A man tries-on a new tie. If the tie pleases his wife then the man buys it.
ACE construction rules require that each noun be introduced by a determiner (a, every, no, some, at least 5, ...). Regarding the list of examples above, ACE interpretation rules decide that (1) is interpreted as universally quantified, while (2) is interpreted as existentially quantified. Sentences like "Women are human" do not follow ACE syntax and are consequently not valid.
Interpretation rules resolve the anaphoric references in (3): the tie and it of the second sentence refer to a new tie of the first sentence, while his and the man of the second sentence refer to a man of the first sentence. Thus an ACE text is a coherent entity of anaphorically linked sentences.
The Attempto Parsing Engine (APE) translates ACE texts unambiguously into discourse representation structures (DRS) that use a variant of the language of first-order logic. A DRS can be further translated into other formal languages, for instance AceRules with various semantics,   OWL, and SWRL. Translating an ACE text into (a fragment of) first-order logic allows users to  reason about the text, for instance to verify, to validate, and to query it.

## Related

- [[Arabic Ontology]]
- [[ChatScript]]
- [[Document classification]]
- [[Gellish English]]
- [[Logic form]]
- [[Natural Language Toolkit]]
- [[NetMiner]]
- [[Rhetorical structure theory]]
- [[Syntactic parsing (computational linguistics)]]
- [[4E cognition]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Attempto_Controlled_English