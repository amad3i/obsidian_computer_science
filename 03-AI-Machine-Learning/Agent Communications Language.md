---
title: "Agent Communications Language"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Agent_Communications_Language"
wikipedia_categories: ["Agent communications languages", "Formal languages", "Knowledge representation"]
related: ["[[4E cognition]]", "[[Abstract family of acceptors]]", "[[Abstract family of languages]]", "[[Abstract rewriting system]]", "[[Abstract semantic graph]]", "[[Abstract syntax tree]]", "[[Action algebra]]", "[[Adaptive grammar]]", "[[Affix grammar]]", "[[Agentive logic]]"]
---

# Agent Communications Language

Agent Communication Language (ACL) consists of computer communication protocols that are intended for AI agents to communicate with each other.
In 2007, protocols of this nature were proposed which include:

FIPA-ACL (by the Foundation for Intelligent Physical Agents, a standardization consortium)
KQML (Knowledge Query and Manipulation Language)
After the surge in generative AI with the use of Transformers and Large language models, the definition of agent has shifted away from physical agents to signify software systems built using the principles of Agentic AI. A new protocol to emerge in this area is Natural Language Interaction Protocol (NLIP). NLIP is an application-level communication protocol defined between AI Agents or between a human and an AI agent. Ecma International; a standards body which develops and publishes international standards for the information and communication industry; published on 10 December 2025 five new standards and one technical report defining the Natural Language Interaction Protocol (NLIP). 
As a result, we can define agent communication protocols into two categories: ontology based agent communication protocols and generative AI based agent communication protocols.
Ontology based agent communication protocols use a common ontology to be used between agents. An ontology is a part of the agent's knowledge base that describes what kind of things an agent can deal with and how they are related to each other. FIPA-ACL and KQML are examples of such protocols. These protocols rely on speech act theory developed by Searle in the 1960s and enhanced by Winograd and Flores in the 1970s. They define a set of performatives, also called Communicative Acts, and their meaning (e.g. ask-one). The content of the performative is not standardized, but varies from system to system.  Implementation support of FIPA-ACL is included in FIPA-OS
and Jade.
Generative AI based agent communication protocols such as NLIP do not require a shared ontology among communicating agents. In its stead, they use generative AI models to translate natural language text, images, videos or other modalities of data into a local ontology. This provides for hot-extensibility where the same protocol can be used for multiple communication needs, and simplifies version control since different agents can use different versions of a shared ontology. 
NLIP has been designed with security considerations in mind. The specification and standards comprising NLIP are developed and maintained by Ecma Technical Community 56.
Another emerging approach is Inthon, a domain-specific programming language layer designed for AI-native workflows and agent orchestration. Unlike traditional communication protocols that focus on inter-agent messaging, Inthon provides a grammar for expressing agent execution intent, including tool calls, memory operations, and policy constraints, within a sandboxed environment. It is implemented as a Python-hosted language and includes features such as a capability-based security model and a bytecode virtual machine for executing agent logic. While not a communication protocol per se, Inthon's design addresses challenges in how agents specify and execute their plans, which includes interactions with external tools and services.

## Related

- [[4E cognition]]
- [[Abstract family of acceptors]]
- [[Abstract family of languages]]
- [[Abstract rewriting system]]
- [[Abstract semantic graph]]
- [[Abstract syntax tree]]
- [[Action algebra]]
- [[Adaptive grammar]]
- [[Affix grammar]]
- [[Agentive logic]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Agent_Communications_Language