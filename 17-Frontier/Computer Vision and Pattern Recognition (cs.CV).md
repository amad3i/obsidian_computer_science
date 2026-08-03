---
title: "Computer Vision and Pattern Recognition"
tags: [cs, frontier, arxiv]
domain: Frontier
level: frontier
source: "https://arxiv.org/list/cs.CV/recent"
---

# Computer Vision and Pattern Recognition (cs.CV)

Frontier research area. Live listing: https://arxiv.org/list/cs.CV/recent

## Recent papers (real, from arXiv)

### Toward Robust and 3D-Aware RGB-NIR Imaging in the Dark

Robust low-light imaging remains challenging for the community. Recent studies have explored fusing Near-Infrared (NIR) with noisy RGB to achieve improved enhancement, yet most methods depend on carefully curated training data pairs, with limited robustness under different scenarios. This paper offers a new perspective for RGB-NIR low-light imaging by incorporating 3D-aware neural modeling. Without using clean RGB supervision, a powerful model can be optimized to implicitly fuse extremely noisy RGB observations with NIR cues in 3D space, effectively recovering clean RGB images. The proposed model obviates the requirement for clean RGB data collection, generalizes across different noise levels. Extensive evaluations on synthetic and real data demonstrate its superiority. Codes available: https://github.com/MyNiuuu/3DarkFusion

- http://arxiv.org/abs/2607.29684v1

### Scaling Properties of Text Conditioning in Visual Generation

We study empirical scaling properties for text conditioning in visual generation. Such properties have rarely been measured because diffusion loss does not scale with the number of tokens in natural-language prompts. Surprisingly, we find that the converged diffusion loss scales with the amount of structured language in the prompt. To quantify structured language, we adapt two complementary measures: a white-box likelihood metric (GPG) and a black-box attribute metric (ED). Across controlled training runs, the converged diffusion loss decreases approximately linearly with GPG and follows a power law with ED. Guided by these scaling properties, we improve \emph{diffusability} by constructing structured prompts with semantic and geometric annotations derived from images, and improve \emph{promptability} by training a prompter through supervised fine-tuning, cold-start, and verifier-gated o

- http://arxiv.org/abs/2607.29679v1

### HierDoc: Hierarchical Page-to-Region Evidence Routing for Long-Document Visual Question Answering

Multi-page document visual question answering requires locating sparse evidence at both the page and region levels. Existing approaches typically emphasize one level over the other: page-centric methods focus on page acquisition, with region operations serving mainly as navigation aids, whereas region-centric methods assume that the relevant pages have already been supplied. Consequently, page and region selection remain disconnected rather than forming successive evidence decisions. We propose HierDoc, a hierarchical evidence-routing framework that formulates long-document evidence acquisition as two-stage set prediction from pages to regions. A page policy selects evidence pages from the full document; these pages are then parsed for semantic elements, after which a region policy selects the elements passed to a downstream answer model. Both answer-agnostic policies are optimized with 

- http://arxiv.org/abs/2607.29638v1

## Sources

- https://arxiv.org/list/cs.CV/recent