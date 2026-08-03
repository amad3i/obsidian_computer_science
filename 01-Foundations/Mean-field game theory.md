---
title: "Mean-field game theory"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Mean-field_game_theory"
wikipedia_categories: ["Game theory", "Mathematical economics"]
related: ["[[Contract theory]]", "[[Game theory]]", "[[Kuhn's theorem]]", "[[Median voter theorem]]", "[[Minimum effort game]]", "[[Perfect recall (game theory)]]", "[[Ambiguity aversion]]", "[[Analytic narrative]]", "[[Asynchrony (game theory)]]", "[[Aumann's agreement theorem]]"]
---

# Mean-field game theory

Mean-field game theory is the study of strategic decision making by small interacting agents in very large populations. It lies at the intersection of game theory with stochastic analysis and control theory. The use of the term "mean field" is inspired by mean-field theory in physics, which considers the behavior of systems of large numbers of particles where individual particles have negligible impacts upon the system. In other words, each agent acts according to his minimization or maximization problem taking into account other agents’ decisions and because their population is large we can assume the number of agents goes to infinity and a representative agent exists. 
In traditional game theory, the subject of study is usually a game with two players and discrete time space, and extends the results to more complex situations by induction. However, for games in continuous time with continuous states (differential games or stochastic differential games) this strategy cannot be used because of the complexity that the dynamic interactions generate. On the other hand with MFGs we can handle large numbers of players through the mean representative agent and at the same time describe complex state dynamics.
This class of problems was considered in the economics literature by Boyan Jovanovic and Robert W. Rosenthal, in the engineering literature by Minyi Huang, Roland Malhame, and Peter E. Caines and independently and around the same time by mathematicians Jean-Michel Lasry and Pierre-Louis Lions.
In continuous time a mean-field game is typically composed of a Hamilton–Jacobi–Bellman equation that describes the optimal control problem of an individual and a Fokker–Planck equation that describes the dynamics of the aggregate distribution of agents. Under fairly general assumptions it can be proved that a class of mean-field games is the limit as 
  
    
      
        N
        →
        ∞
      
    
    
  
 of an N-player Nash equilibrium.
A related concept to that of mean-field games is "mean-field-type control". In this case, a social planner controls the distribution of states and chooses a control strategy. The solution to a mean-field-type control problem can typically be expressed as a dual adjoint Hamilton–Jacobi–Bellman equation coupled with Kolmogorov equation. Mean-field-type game theory is the multi-agent generalization of the single-agent mean-field-type control.

## Related

- [[Contract theory]]
- [[Game theory]]
- [[Kuhn's theorem]]
- [[Median voter theorem]]
- [[Minimum effort game]]
- [[Perfect recall (game theory)]]
- [[Ambiguity aversion]]
- [[Analytic narrative]]
- [[Asynchrony (game theory)]]
- [[Aumann's agreement theorem]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Mean-field_game_theory