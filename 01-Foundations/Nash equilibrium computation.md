---
title: "Nash equilibrium computation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Nash_equilibrium_computation"
wikipedia_categories: ["Computational economics", "Game theory"]
related: ["[[Ambiguity aversion]]", "[[Analytic narrative]]", "[[Asynchrony (game theory)]]", "[[Aumann's agreement theorem]]", "[[Authority distribution]]", "[[Backward induction]]", "[[Banzhaf power index]]", "[[Bayesian efficiency]]", "[[Bayesian regret]]", "[[Behavioral game theory]]"]
---

# Nash equilibrium computation

Nash equilibrium (NE) computation is a class of computational problems in the intersection of game theory and computer science. The input to this problem is a normal-form game, usually represented as a list of payoff matrices. The required output is a Nash equilibrium of the game.
NE computation can be broadly divided into computing mixed-strategy NE vs computing pure-strategy NE.  In each of these cases, one can consider computing an exact NE or an epsilon-approximate NE:

In an exact NE, no player can gain by deviating;
In an epsilon-approximate NE, no player can gain more than epsilon by deviating. The utilities are normalized to [0,1], so this is actually a multiplicative approximation: the gain cannot be more than epsilon times the highest utility.
The special case of NE computation in two-player zero-sum games is known as min-max optimization. The present page studies the more general problem of non-zero-sum games with many players.

## Related

- [[Ambiguity aversion]]
- [[Analytic narrative]]
- [[Asynchrony (game theory)]]
- [[Aumann's agreement theorem]]
- [[Authority distribution]]
- [[Backward induction]]
- [[Banzhaf power index]]
- [[Bayesian efficiency]]
- [[Bayesian regret]]
- [[Behavioral game theory]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Nash_equilibrium_computation