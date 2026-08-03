---
title: "Software Engineering"
tags: [cs, frontier, arxiv]
domain: Frontier
level: frontier
source: "https://arxiv.org/list/cs.SE/recent"
---

# Software Engineering (cs.SE)

Frontier research area. Live listing: https://arxiv.org/list/cs.SE/recent

## Recent papers (real, from arXiv)

### Reusing Past Repairs Through Hierarchical Trajectory Abstraction for Coding Agents

Although LLM-driven repair agents can tackle complex, repository-level issues, they treat every issue independently and discard the procedural knowledge accumulated from previous repairs. We introduce STAIR, a framework that converts historical repair trajectories into hierarchical, reusable plans that can be adapted to steer future repairs. Each past trajectory is transformed into a multi-level tree that ranges from fine-grained diagnostic actions to high-level repair strategies, encoding experience at several granularities. When a new issue arrives, STAIR selects relevant plan nodes from multiple abstraction levels, tailors them into executable, issue-specific plans, and supplies them to the agent through its prompt. On SWE-bench Verified, STAIR integrated with Lingxi reaches 81.2% Pass@1 using MiniMax M2.5 and 79.2% using GPT-5. The generated plans also generalize across agents: witho

- http://arxiv.org/abs/2607.29658v1

### CodeShrink: Adaptive Visual Compression for Efficient Multimodal Code Understanding

Rendering source code as images offers a promising way to reduce the input costs of Multimodal Large Language Models (MLLMs). Adjusting image resolution can trade visual token cost against content fidelity. However, resolution scaling alone overlooks two sources of inefficiency: blank regions created by line breaks and indentation, and code regions irrelevant to the current instruction. Moreover, the best compression setting varies across inputs, tasks, and models, limiting fixed-ratio strategies. We propose CodeShrink, an adaptive visual compression framework with three components. Blank-Free Rendering replaces whitespace-dependent layouts with compact layouts and explicit structural markers, removing layout-induced tokens. Adaptive Compression Configuration uses a lightweight agent trained with reinforcement learning to predict a per-input setting that balances token efficiency and rea

- http://arxiv.org/abs/2607.29637v1

### Educating the Agentic Engineer: Curricula, Collaboration, and Continuous Learning in the AI Era

Generative and agentic artificial intelligence (AI) are reconfiguring software and systems engineering from a discipline centered on human authorship of artifacts to one focused on directing, verifying, and governing autonomous systems. This transition demands a new professional archetype, the \emph{agentic engineer}, whose enduring value lies in intent specification, orchestration of multi-agent workflows, critical evaluation of machine-generated outputs, and ethical judgment. This article presents an integrative conceptual synthesis across engineering education, computing education, human--AI interaction, human factors, and the learning sciences to derive an evidence-grounded educational architecture for this archetype. We introduce the ACCEL framework (Agentic Competencies through Curricula, Collaboration, and Enduring Learning), which organizes five competency pillars and maps them t

- http://arxiv.org/abs/2607.29610v1

## Sources

- https://arxiv.org/list/cs.SE/recent