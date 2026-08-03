---
title: "HYPO CBR"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/HYPO_CBR"
wikipedia_categories: ["Argument technology", "Expert systems", "Legal software", "Software programmed in Prolog"]
related: ["[[Legal expert system]]", "[[Shyster (expert system)]]", "[[Split Up (expert system)]]", "[[Lawbot]]", "[[Akoma Ntoso]]", "[[Argument mining]]", "[[Artificial intelligence in fraud detection]]", "[[Backward chaining]]", "[[Business rule management system]]", "[[Business rules engine]]"]
---

# HYPO CBR

HYPO is a computer program, an expert system, that models reasoning with cases and hypotheticals in the legal domain. It is the first of its kind and the most sophisticated of the case-based legal reasoners, which was designed by Kevin Ashley for his Ph.D dissertation in 1987 at the University of Massachusetts Amherst under the supervision of Edwina Rissland. HYPO's design represents a hybrid generalization/comparative evaluation method appropriate for a domain with a weak analytical theory and applies to tasks that rarely involve just one right answer. The domain covers US trade secret law, and is substantially a common law domain. Since Anglo-American common law operates under the doctrine of precedent, the definitive way of interpreting problems is of necessity and case-based. Thus, HYPO did not involve the analysis of a statute, as required by the Prolog program. Rissland and Ashley (1987) envisioned HYPO as employing the key tasks performed by lawyers when analyzing case law for precedence to generate arguments for the prosecution or the defence.
HYPO was a successful example of a general category of legal expert systems (LESs), it applies artificial intelligence (A.I.) techniques to the domain of legal reasoning in patent law, implementing a case-based reasoning (CBR) system, in contrast to rule based systems like MYCIN, or mixed-paradigm systems integrating CBR with rule-based or model-based reasoning like IKBALS II. A legal case-based reasoning essentially reasons from prior tried cases, comparing the contextual information in the current input case with that of cases previously tried and entered into the system. As noted by Ashley and Rissland (1988) CBR is used to "... capture expertise in domains where rules are ill-defined, incomplete or inconsistent".
The HYPO project set out to model the creation of hypotheticals in law, where no case matches well enough. HYPO uses hypotheticals for a variety of tasks necessary for good interpretation: "to redefine old situations in terms of new dimensions, to create new standard cases when an appropriate one doesn’t exist, to explore and test the limits of a concept, to refocus a case by excluding some issues and to organize or cluster cases". Hypotheticals can include facts that support two conflicting lines of reasoning. So, it makes and responds to arguments from competing viewpoints about who should win the dispute. HYPO use heuristics such as making a case weaker or stronger, making a case extreme, enabling a near-miss, disabling a near-hit to generate hypotheticals in the context of an argument by using the dimensions mechanism. Dimensions have a range of values, along which the supportive strength that may shift from one side to the other. What differentiated this expert system from others was its facility not only to return a primary to best-case response but to return near-best-fit responses also.

## Related

- [[Legal expert system]]
- [[Shyster (expert system)]]
- [[Split Up (expert system)]]
- [[Lawbot]]
- [[Akoma Ntoso]]
- [[Argument mining]]
- [[Artificial intelligence in fraud detection]]
- [[Backward chaining]]
- [[Business rule management system]]
- [[Business rules engine]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/HYPO_CBR