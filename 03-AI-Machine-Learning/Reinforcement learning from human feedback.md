---
title: "Reinforcement learning from human feedback"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Reinforcement_learning_from_human_feedback"
wikipedia_categories: ["2017 in artificial intelligence", "Language modeling", "Reinforcement learning"]
related: ["[[OpenAI Five]]", "[[Proximal policy optimization]]", "[[2017 in artificial intelligence]]", "[[Actor-critic algorithm]]", "[[AlphaChip]]", "[[Brown clustering]]", "[[Cache language model]]", "[[Deep reinforcement learning]]", "[[Distributional Soft Actor Critic]]", "[[Distributional–relational database]]"]
---

# Reinforcement learning from human feedback

In machine learning, reinforcement learning from human feedback (RLHF) is a technique to align an intelligent agent with human preferences. It involves training a reward model to represent preferences, which can then be used to train other models through reinforcement learning.
In classical reinforcement learning, an intelligent agent's goal is to learn a function that guides its behavior, called a policy. The function is iteratively optimized to increase the reward signal derived from the agent's task performance. However, explicitly defining a reward function that accurately approximates human preferences is challenging. Therefore, RLHF seeks to train a "reward model" directly from human feedback. The reward model is first trained in a supervised manner to predict if a response to a given prompt is good (high reward) or bad (low reward) based on ranking data collected from human annotators. This model then serves as a reward function to improve an agent's policy through an optimization algorithm like proximal policy optimization.
RLHF has applications in various domains in machine learning, including natural language processing tasks such as text summarization and conversational agents, computer vision tasks like text-to-image models, and the development of video game bots. While RLHF is an effective method of training models to act better in accordance with human preferences, it also faces challenges due to the way the human preference data is collected. Though RLHF does not require massive amounts of data to improve performance, sourcing high-quality preference data is still an expensive process. Furthermore, if the data is not carefully collected from a representative sample, the resulting model may exhibit unwanted biases.

## Related

- [[OpenAI Five]]
- [[Proximal policy optimization]]
- [[2017 in artificial intelligence]]
- [[Actor-critic algorithm]]
- [[AlphaChip]]
- [[Brown clustering]]
- [[Cache language model]]
- [[Deep reinforcement learning]]
- [[Distributional Soft Actor Critic]]
- [[Distributional–relational database]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Reinforcement_learning_from_human_feedback