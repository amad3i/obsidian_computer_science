---
title: "Context-sensitive grammar"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/Context-sensitive_grammar"
wikipedia_categories: ["Formal languages", "Grammar frameworks"]
related: ["[[Affix grammar]]", "[[Categorial grammar]]", "[[Controlled grammar]]", "[[Discontinuous-constituent phrase structure grammar]]", "[[Extended affix grammar]]", "[[Generalized context-free grammar]]", "[[Global index grammar]]", "[[Head grammar]]", "[[Indexed grammar]]", "[[Literal movement grammar]]"]
---

# Context-sensitive grammar

A context-sensitive grammar (CSG) is a formal grammar in which the left-hand sides and right-hand sides of any production rules may be surrounded by a context of terminal and nonterminal symbols. Context-sensitive grammars are more general than context-free grammars, in the sense that there are languages that can be described by a CSG but not by a context-free grammar. Context-sensitive grammars are less general (in the same sense) than unrestricted grammars. Thus, CSGs are positioned between context-free and unrestricted grammars in the Chomsky hierarchy.
A formal language that can be described by a context-sensitive grammar, or, equivalently, by a noncontracting grammar or a linear bounded automaton, is called a context-sensitive language. Some textbooks actually define CSGs as non-contracting, although this is not how Noam Chomsky defined them in 1959. This choice of definition makes no difference in terms of the languages generated (i.e. the two definitions are weakly equivalent), but it does make a difference in terms of what grammars are structurally considered context-sensitive; the latter issue was analyzed by Chomsky in 1963.
Chomsky introduced context-sensitive grammars as a way to describe the syntax of natural language where it is often the case that a word may or may not be appropriate in a certain place depending on the context. Walter Savitch has criticized the terminology "context-sensitive" as misleading and proposed "non-erasing" as better explaining the distinction between a CSG and an unrestricted grammar.
Although it is well known that certain features of languages (e.g. cross-serial dependency) are not context-free, it is an open question how much of CSGs' expressive power is needed to capture the context sensitivity found in natural languages. Subsequent research in this area has focused on the more computationally tractable mildly context-sensitive languages. The syntaxes of some visual programming languages can be described by context-sensitive graph grammars.

## Related

- [[Affix grammar]]
- [[Categorial grammar]]
- [[Controlled grammar]]
- [[Discontinuous-constituent phrase structure grammar]]
- [[Extended affix grammar]]
- [[Generalized context-free grammar]]
- [[Global index grammar]]
- [[Head grammar]]
- [[Indexed grammar]]
- [[Literal movement grammar]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Context-sensitive_grammar