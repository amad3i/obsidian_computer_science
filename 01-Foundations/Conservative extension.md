---
title: "Conservative extension"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Conservative_extension"
wikipedia_categories: ["Mathematical logic", "Model theory", "Proof theory"]
related: ["[[Completeness (logic)]]", "[[Gödel's incompleteness theorems]]", "[[Original proof of Gödel's completeness theorem]]", "[[Abstract model theory]]", "[[Beth definability]]", "[[Brouwer–Heyting–Kolmogorov interpretation]]", "[[Büchi arithmetic]]", "[[Categorical theory]]", "[[Compactness theorem]]", "[[Complete theory]]"]
---

# Conservative extension

In mathematical logic, a conservative extension is a supertheory of a theory which is often convenient for proving theorems, but proves no new theorems about the language of the original theory. Similarly, a non-conservative extension, or proper extension, is a supertheory which is not conservative, and can prove more theorems than the original.
More formally stated, a theory T2 is a (proof theoretic) conservative extension of a theory T1 if every theorem of T1 is a theorem of T2, and any theorem of T2 in the language of T1 is already a theorem of T1.
More generally, if Γ is a set of formulas in the common language of T1 and T2, then T2 is Γ-conservative over T1 if every formula from Γ provable in T2 is also provable in T1.
Note that a conservative extension of a consistent theory is consistent. If it were not, then by the principle of explosion, every formula in the language of T2 would be a theorem of T2, so every formula in the language of T1 would be a theorem of T1, so T1 would not be consistent. Hence, conservative extensions do not bear the risk of introducing new inconsistencies. This can also be seen as a methodology for writing and structuring large theories: start with a theory, T0, that is known (or assumed) to be consistent, and successively build conservative extensions T1, T2, … of it.
Recently, conservative extensions have been used for defining a notion of module for ontologies: if an ontology is formalized as a logical theory, a subtheory is a module if the whole ontology is a conservative extension of the subtheory.

## Related

- [[Completeness (logic)]]
- [[Gödel's incompleteness theorems]]
- [[Original proof of Gödel's completeness theorem]]
- [[Abstract model theory]]
- [[Beth definability]]
- [[Brouwer–Heyting–Kolmogorov interpretation]]
- [[Büchi arithmetic]]
- [[Categorical theory]]
- [[Compactness theorem]]
- [[Complete theory]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Conservative_extension