---
title: "Agent harness"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Agent_harness"
wikipedia_categories: ["Application software suites", "Artificial intelligence", "Large language models"]
related: ["[[AI data center]]", "[[AI observability]]", "[[Competition in artificial intelligence]]", "[[Feedback neural network]]", "[[GPT-5.6]]", "[[LLM-as-a-Judge]]", "[[Muse Spark]]", "[[PagedAttention]]", "[[Sycophancy (artificial intelligence)]]", "[[ai]]"]
---

# Agent harness

An agent harness is the software infrastructure surrounding a large language model (LLM) that enables it to operate as an AI agent: it manages tool use, memory, state persistence, execution environments and feedback loops, as opposed to the model's own reasoning. A shorthand popularised in 2026 expresses the relationship as Agent = Model + Harness.
Because an LLM is stateless and, unaided, produces only text, the harness is what allows a model to take actions over multiple steps, use external tools, and sustain a long-running task across sessions. Rather than repeatedly re-reading an ever-growing transcript inside the context window, a harness can offload record-keeping into a structured software environment that manages the agent's state. A minimal harness is unnecessary for a single prompt-and-response exchange, but becomes important as tasks grow multi-step, tool-oriented, or long-running.

## Related

- [[AI data center]]
- [[AI observability]]
- [[Competition in artificial intelligence]]
- [[Feedback neural network]]
- [[GPT-5.6]]
- [[LLM-as-a-Judge]]
- [[Muse Spark]]
- [[PagedAttention]]
- [[Sycophancy (artificial intelligence)]]
- [[ai]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Agent_harness