---
title: "AI observability"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/AI_observability"
wikipedia_categories: ["Artificial intelligence", "Large language models", "Machine learning", "Software engineering"]
related: ["[[AI data center]]", "[[LLM-as-a-Judge]]", "[[Sycophancy (artificial intelligence)]]", "[[Agent harness]]", "[[AIOps]]", "[[Automated machine learning]]", "[[Claude (AI)]]", "[[Competition in artificial intelligence]]", "[[Dataset shift]]", "[[Feedback neural network]]"]
---

# AI observability

AI observability is the practice of collecting and analyzing telemetry, data such as logs, metrics, and traces that a system automatically records as it runs, from artificial intelligence systems deployed in production, in order to understand how they behave and how well they perform in terms of accuracy, cost, and safety. It applies the idea of observability, which comes from control theory and software engineering, to systems based on machine learning models, and in particular to large language models (LLMs) and autonomous agents. In control theory, observability is a measure of how well the internal state of a system can be inferred from its external outputs.
AI observability is often distinguished from conventional monitoring. Where monitoring relies on predefined metrics, thresholds, and alerts to signal that a problem has occurred, observability aims to provide enough context to understand why it occurred. The distinction matters for AI systems in particular, because a system can appear healthy by standard infrastructure measures, such as latency or error rate, while still producing answers that are wrong, irrelevant, or unsafe.
One of the signals that AI observability tracks is the change in a model's behavior over time, a phenomenon studied in machine learning under the name of concept drift. AI observability is closely related to MLOps (machine learning operations), and it is sometimes treated as one of its parts. When it is applied specifically to language models or to agent-based systems, it is also called LLM observability or agent observability.

## Related

- [[AI data center]]
- [[LLM-as-a-Judge]]
- [[Sycophancy (artificial intelligence)]]
- [[Agent harness]]
- [[AIOps]]
- [[Automated machine learning]]
- [[Claude (AI)]]
- [[Competition in artificial intelligence]]
- [[Dataset shift]]
- [[Feedback neural network]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/AI_observability