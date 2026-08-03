---
title: "Tournament selection"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Tournament_selection"
wikipedia_categories: ["Selection (evolutionary algorithm)"]
related: ["[[Fitness proportionate selection]]", "[[Reward-based selection]]", "[[Stochastic universal sampling]]", "[[Truncation selection]]"]
---

# Tournament selection

Tournament selection is a method of selecting an individual from a population of individuals in a evolutionary algorithm. Tournament selection involves running several "tournaments" among a few individuals (or "chromosomes") chosen at random from the population.  The winner of each tournament (the one with the best fitness) is selected for crossover.  
Selection pressure is then a probabilistic measure of a chromosome's likelihood of participation in the tournament based on the participant selection pool size, is easily adjusted by changing the tournament size. The reason is that if the tournament size is larger, weak individuals have a smaller chance to be selected, because, if a weak individual is selected to be in a tournament, there is a higher probability that a stronger individual is also in that tournament.

## Related

- [[Fitness proportionate selection]]
- [[Reward-based selection]]
- [[Stochastic universal sampling]]
- [[Truncation selection]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Tournament_selection