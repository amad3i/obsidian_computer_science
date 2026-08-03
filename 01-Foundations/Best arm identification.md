---
title: "Best arm identification"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Best_arm_identification"
wikipedia_categories: ["Algorithms", "Decision theory", "Optimization algorithms and methods", "Sequential methods", "Stochastic optimization"]
related: ["[[Explore-then-commit algorithm]]", "[[Kullback–Leibler Upper Confidence Bound]]", "[[Lai–Robbins lower bound]]", "[[Algorithm IMED]]", "[[Bayesian optimization]]", "[[Communication-avoiding algorithm]]", "[[Divide-and-conquer algorithm]]", "[[Least-squares spectral analysis]]", "[[List of algorithms]]", "[[Minimax]]"]
---

# Best arm identification

Best arm identification (BAI) is a sequential one-player game where the player has to find the best action (arm) among a list of actions (arms) by collecting information in the most efficient way.
It is a multi-armed bandit game as a player only gets information about an arm by playing it. The most common objective in multi-armed bandit games is to minimize the regret (i.e., play the best action as much as possible), but in BAI, the goal is to find the best arm as efficiently as possible.
This problem naturally arises in scenarios such as adaptive clinical trials where the number of patients is limited and the quantification of the confidence in a treatment is important. It also arises in hyperparameter optimization where the goal is to find the optimal choice of hyperparameters for an algorithm with the smallest possible number of experiments, as it can be costly in terms of time, energy, or money.

## Related

- [[Explore-then-commit algorithm]]
- [[Kullback–Leibler Upper Confidence Bound]]
- [[Lai–Robbins lower bound]]
- [[Algorithm IMED]]
- [[Bayesian optimization]]
- [[Communication-avoiding algorithm]]
- [[Divide-and-conquer algorithm]]
- [[Least-squares spectral analysis]]
- [[List of algorithms]]
- [[Minimax]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Best_arm_identification