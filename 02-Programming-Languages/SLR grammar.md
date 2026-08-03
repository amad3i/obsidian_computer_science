---
title: "SLR grammar"
tags: ["cs", "programming-languages", "intermediate"]
domain: Programming & Languages
level: intermediate
source: "https://en.wikipedia.org/wiki/SLR_grammar"
wikipedia_categories: ["Formal languages"]
related: ["[[Abstract family of acceptors]]", "[[Abstract family of languages]]", "[[Abstract rewriting system]]", "[[Abstract semantic graph]]", "[[Abstract syntax tree]]", "[[Action algebra]]", "[[Adaptive grammar]]", "[[Affix grammar]]", "[[Agent Communications Language]]", "[[Algorithmic learning theory]]"]
---

# SLR grammar

SLR grammars are the class of formal grammars accepted by a Simple LR parser.  SLR grammars are a superset of all LR(0) grammars and a subset of all LALR(1) and LR(1) grammars.
When processed by an SLR parser, an SLR grammar is converted into parse tables with no shift/reduce or reduce/reduce conflicts for any combination of LR(0) parser state and expected lookahead symbol.  If the grammar is not SLR, the parse tables will have shift/reduce conflicts or reduce/reduce conflicts for some state and some lookahead symbols, and the resulting rejected parser is no longer deterministic.  The parser cannot decide whether to shift or reduce next, or cannot decide between two candidate reductions.  SLR parsers use a Follow(A) calculation to pick the lookahead symbols to expect for every completed nonterminal.  
LALR parsers use a different calculation which sometimes gives smaller, tighter lookahead sets for the same parser states.  Those smaller sets can eliminate overlap with the state's shift actions, and overlap with lookaheads for other reductions in this same state.  The overlap conflicts reported by SLR parsers are then spurious, a result of the approximate calculation using Follow(A).
A grammar which is ambiguous will have unavoidable shift/reduce conflicts or reduce/reduce conflicts for every LR analysis method, including SLR.  A common way for computer language grammars to be ambiguous is if some nonterminal is both left- and right-recursive:

Expr → Expr * Val
Expr → Val + Expr
Expr → Val

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

- Wikipedia: https://en.wikipedia.org/wiki/SLR_grammar