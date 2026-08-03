---
title: "Q-learning"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Q-learning"
wikipedia_categories: ["1989 in artificial intelligence", "Machine learning algorithms", "Reinforcement learning"]
related: ["[[Actor-critic algorithm]]", "[[Deep reinforcement learning]]", "[[Distributional Soft Actor Critic]]", "[[Policy gradient method]]", "[[Proximal policy optimization]]", "[[Self-play]]", "[[State–action–reward–state–action]]", "[[AdaBoost]]", "[[Algorithms of Oppression]]", "[[Almeida–Pineda recurrent backpropagation]]"]
---

# Q-learning

Q-learning is a reinforcement learning algorithm that trains an agent to assign values to its possible actions based on its current state, without requiring a model of the environment (model-free). It can handle problems with stochastic transitions and rewards without requiring adaptations.
For example, in a grid maze, an agent learns to reach an exit worth 10 points. At a junction, Q-learning might assign a higher value to moving right than left if right gets to the exit faster, improving this choice by trying both directions over time.
For any finite Markov decision process, Q-learning finds an optimal policy in the sense of maximizing the expected value of the total reward over any and all successive steps, starting from the current state. Q-learning can identify an optimal action-selection policy for any given finite Markov decision process, given infinite exploration time and a partly random policy. 
"Q" refers to the function that the algorithm computes: the expected reward—that is, the quality—of an action taken in a given state.

## Related

- [[Actor-critic algorithm]]
- [[Deep reinforcement learning]]
- [[Distributional Soft Actor Critic]]
- [[Policy gradient method]]
- [[Proximal policy optimization]]
- [[Self-play]]
- [[State–action–reward–state–action]]
- [[AdaBoost]]
- [[Algorithms of Oppression]]
- [[Almeida–Pineda recurrent backpropagation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Q-learning