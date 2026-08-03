---
title: "Kuroda normal form"
tags: ["cs", "theory-of-computation", "intermediate"]
domain: Theory of Computation
level: intermediate
source: "https://en.wikipedia.org/wiki/Kuroda_normal_form"
wikipedia_categories: ["Formal languages"]
related: ["[[Abstract family of acceptors]]", "[[Abstract family of languages]]", "[[Abstract rewriting system]]", "[[Abstract semantic graph]]", "[[Abstract syntax tree]]", "[[Action algebra]]", "[[Adaptive grammar]]", "[[Affix grammar]]", "[[Agent Communications Language]]", "[[Algorithmic learning theory]]"]
---

# Kuroda normal form

In formal language theory, a noncontracting grammar is in Kuroda normal form if all production rules are of the form:

AB → CD or
A → BC or
A → B or
A → a
where A, B, C and D are nonterminal symbols and a is a terminal symbol. Some sources omit the A → B pattern.
It is named after Sige-Yuki Kuroda, who originally called it a linear bounded grammar, a terminology that was also used by a few other authors thereafter.
Every grammar in Kuroda normal form is noncontracting, and therefore, generates a context-sensitive language.  Conversely, every noncontracting grammar that does not generate the empty string can be converted to Kuroda normal form.
A straightforward technique attributed to György Révész transforms a grammar in Kuroda normal form to a context-sensitive grammar: AB → CD is replaced by four context-sensitive rules AB → AZ, AZ → WZ, WZ → WD and WD → CD. This proves that every noncontracting grammar generates a context-sensitive language.
There is a similar normal form for unrestricted grammars as well, which at least some authors call "Kuroda normal form" too:

AB → CD or
A → BC or
A → a or
A → ε
where ε is the empty string. Every unrestricted grammar is weakly equivalent to one using only productions of this form.
If the rule AB → CD is eliminated from the above, one obtains context-free grammars in Chomsky Normal Form. The Penttonen normal form (for unrestricted grammars) is a special case where first rule above is AB → AD. Similarly, for context-sensitive grammars, the Penttonen normal form, also called the one-sided normal form (following Penttonen's own terminology) is:

AB → AD or
A → BC or
A → a
For every context-sensitive grammar, there exists a weakly equivalent one-sided normal form.

## Related

- [[Abstract family of acceptors]]
- [[Abstract family of languages]]
- [[Abstract rewriting system]]
- [[Abstract semantic graph]]
- [[Abstract syntax tree]]
- [[Action algebra]]
- [[Adaptive grammar]]
- [[Affix grammar]]
- [[Agent Communications Language]]
- [[Algorithmic learning theory]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Kuroda_normal_form