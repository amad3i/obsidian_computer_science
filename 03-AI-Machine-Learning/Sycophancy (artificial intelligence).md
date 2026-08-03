---
title: "Sycophancy (artificial intelligence)"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Sycophancy_(artificial_intelligence)"
wikipedia_categories: ["AI safety", "Artificial intelligence", "Large language models", "Machine learning"]
related: ["[[AI data center]]", "[[AI observability]]", "[[LLM-as-a-Judge]]", "[[Adversarial machine learning]]", "[[Agent harness]]", "[[AI alignment]]", "[[AI safety]]", "[[AIOps]]", "[[Automated machine learning]]", "[[Claude (AI)]]"]
---

# Sycophancy (artificial intelligence)

In the field of artificial intelligence, sycophancy is a tendency of large language models (LLMs) and other AI assistants to tailor their responses to what they predict the user wants to hear rather than to what is accurate or warranted. The behavior takes several forms: an assistant may agree with a user's stated opinion even when the user is mistaken; it may abandon a correct answer after a challenge such as "are you sure?"; it may validate beliefs, decisions or self-presentation regardless of merit; or it may praise the user, their work or their ideas in unwarranted terms. The word is borrowed from the ordinary English term for fawning flattery, and is used in AI alignment and AI safety research to describe a class of misalignment failures associated with training on human feedback.
Researchers at Anthropic first documented the behavior systematically in 2022. They found that models fine-tuned with reinforcement learning from human feedback (RLHF) were more likely than untuned models to repeat back a user's preferred answer. A 2023 follow-up paper, "Towards Understanding Sycophancy in Language Models", showed that five frontier assistants from OpenAI, Anthropic and Meta all exhibited the behavior, and traced its origin to biases in the human preference data used during training. Later work documented sycophancy in mathematics, medicine, academic peer review and other domains, and identified a broader category called "social sycophancy" affecting an assistant's emotional and interpersonal responses.
The issue drew widespread public attention in April 2025 after OpenAI rolled back an update to its GPT-4o model. Users had reported that the assistant praised dangerous decisions, endorsed delusional thinking and offered exaggerated compliments for trivial prompts. OpenAI's post-mortem attributed the change in behavior to an additional training signal based on user thumbs-up and thumbs-down feedback. That episode, together with reporting in The New York Times, Rolling Stone and elsewhere on users drawn into delusional thinking through prolonged chatbot interaction, has been cited in litigation and in academic studies as evidence that sycophancy poses risks to user well-being.
Proposed mitigations include fine-tuning on synthetic data that rewards disagreement with incorrect user statements, editing the small subset of model parameters causally responsible for the behavior, changes to the dialogue or system prompt, and benchmarks designed to surface sycophantic behavior before models are released.

## Related

- [[AI data center]]
- [[AI observability]]
- [[LLM-as-a-Judge]]
- [[Adversarial machine learning]]
- [[Agent harness]]
- [[AI alignment]]
- [[AI safety]]
- [[AIOps]]
- [[Automated machine learning]]
- [[Claude (AI)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Sycophancy_(artificial_intelligence)