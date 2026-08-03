---
title: "Knowledge cutoff"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Knowledge_cutoff"
wikipedia_categories: ["Artificial intelligence", "Machine learning algorithms", "Natural language processing"]
related: ["[[Zero-shot learning]]", "[[Actor-critic algorithm]]", "[[AI data center]]", "[[Augmented Analytics]]", "[[Limited Memory AI]]", "[[List of artificial intelligence algorithms]]", "[[LLM-as-a-Judge]]", "[[MAUVE (metric)]]", "[[Speculative decoding]]", "[[ai]]"]
---

# Knowledge cutoff

In machine learning, a knowledge cutoff (or data cutoff) is the point in time beyond which a model has not been trained on new data. The term is used in reference to large language models. Large language models are pretrained ahead of time. After that, the model's knowledge is fixed. Any information about events after this date is absent from the model's training data. The model cannot access information about later events without a system for real-time data access like retrieval-augmented generation, which is a technique that fetches new information from an external database. While simple for training and tuning large language models, knowledge cutoffs introduce new limitations like hallucinations, where the model generates confident but false statements, information gaps, and reduced accuracy on evolving knowledge. Research has shown that knowledge cutoffs have safety-critical implications, particularly in domains like healthcare, where outdated knowledge can lead to harmful recommendations. A later knowledge cutoff may achieve higher accuracy in time-sensitive tasks.

## Related

- [[Zero-shot learning]]
- [[Actor-critic algorithm]]
- [[AI data center]]
- [[Augmented Analytics]]
- [[Limited Memory AI]]
- [[List of artificial intelligence algorithms]]
- [[LLM-as-a-Judge]]
- [[MAUVE (metric)]]
- [[Speculative decoding]]
- [[ai]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Knowledge_cutoff