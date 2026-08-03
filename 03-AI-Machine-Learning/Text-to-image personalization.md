---
title: "Text-to-image personalization"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Text-to-image_personalization"
wikipedia_categories: ["Computer graphics", "Deep learning", "Text-to-image generation"]
related: ["[[Digital cloning]]", "[[Latent diffusion model]]", "[[2D computer graphics]]", "[[3D computer graphics]]", "[[3D lookup table]]", "[[4D reconstruction]]", "[[9-slice scaling]]", "[[A-buffer]]", "[[ACM Transactions on Graphics]]", "[[Adaptive tile refresh]]"]
---

# Text-to-image personalization

Text-to-Image personalization is a task in deep learning for computer graphics that augments pre-trained text-to-image generative models. In this task, a generative model that was trained on large-scale data (usually a foundation model), is adapted such that it can generate images of novel, user-provided concepts. These concepts are typically unseen during training, and may represent specific objects (such as the user's pet) or more abstract categories (new artistic style or object relations).
Text-to-Image personalization methods typically bind the novel (personal) concept to new words in the vocabulary of the model. These words can then be used in future prompts to invoke the concept for subject-driven generation, inpainting, style transfer and even to correct biases in the model. To do so, models either optimize word-embeddings, fine-tune the generative model itself, or employ a mixture of both approaches.

## Related

- [[Digital cloning]]
- [[Latent diffusion model]]
- [[2D computer graphics]]
- [[3D computer graphics]]
- [[3D lookup table]]
- [[4D reconstruction]]
- [[9-slice scaling]]
- [[A-buffer]]
- [[ACM Transactions on Graphics]]
- [[Adaptive tile refresh]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Text-to-image_personalization