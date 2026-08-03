---
title: "State–action–reward–state–action"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/State–action–reward–state–action"
wikipedia_categories: ["1994 in artificial intelligence", "Machine learning algorithms", "Reinforcement learning"]
related: ["[[Actor-critic algorithm]]", "[[Deep reinforcement learning]]", "[[Distributional Soft Actor Critic]]", "[[Policy gradient method]]", "[[Proximal policy optimization]]", "[[Q-learning]]", "[[Self-play]]", "[[AdaBoost]]", "[[Algorithms of Oppression]]", "[[Almeida–Pineda recurrent backpropagation]]"]
---

# State–action–reward–state–action

State–action–reward–state–action (SARSA) is an algorithm for learning a Markov decision process policy, used in the reinforcement learning area of machine learning. It was proposed by Rummery and Niranjan in a technical note with the name "Modified Connectionist Q-Learning" (MCQ-L). The alternative name SARSA, proposed by Rich Sutton, was only mentioned as a footnote.
This name reflects the fact that the main function for updating the Q-value depends on the current state of the agent "S1", the action the agent chooses "A1", the reward "R2" the agent gets for choosing this action, the state "S2" that the agent enters after taking that action, and finally the next action "A2" the agent chooses in its new state. The acronym for the quintuple (St, At, Rt+1, St+1, At+1) is SARSA. Some authors use a slightly different convention and write the quintuple (St, At, Rt, St+1, At+1), depending on which time step the reward is formally assigned. The rest of the article uses the former convention.

## Related

- [[Actor-critic algorithm]]
- [[Deep reinforcement learning]]
- [[Distributional Soft Actor Critic]]
- [[Policy gradient method]]
- [[Proximal policy optimization]]
- [[Q-learning]]
- [[Self-play]]
- [[AdaBoost]]
- [[Algorithms of Oppression]]
- [[Almeida–Pineda recurrent backpropagation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/State–action–reward–state–action