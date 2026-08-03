---
title: "Fictitious play"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Fictitious_play"
wikipedia_categories: ["Game theory"]
related: ["[[Ambiguity aversion]]", "[[Analytic narrative]]", "[[Asynchrony (game theory)]]", "[[Aumann's agreement theorem]]", "[[Authority distribution]]", "[[Backward induction]]", "[[Banzhaf power index]]", "[[Bayesian efficiency]]", "[[Bayesian regret]]", "[[Behavioral game theory]]"]
---

# Fictitious play

In game theory, fictitious play is a learning rule that describes how players might learn over time in repeated strategic interactions. In fictitious play, each player assumes that opponents are using stationary (possibly mixed) strategies, and responds optimally to the historical empirical distribution of their opponents' past actions. Specifically, at each round, a player calculates the empirical frequency of each strategy their opponents have played in previous rounds and selects their own best response to these frequencies.
This approach provides a simple model of bounded rationality in which players gradually learn about their strategic environment through repeated observation. Fictitious play converges to Nash equilibrium in several important classes of games, including zero-sum games, potential games, and games with dominant strategies. However, the method has notable limitations when opponents employ non-stationary or adaptive strategies. For example, if an opponent conditions their play on the fictitious player's recent moves or deliberately exploits the predictable nature of the best-response pattern, the fictitious play approach may fail to converge or may be systematically exploited.
It was first introduced by mathematician George W. Brown in 1951.

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

- Wikipedia: https://en.wikipedia.org/wiki/Fictitious_play