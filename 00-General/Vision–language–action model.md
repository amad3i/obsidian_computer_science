---
title: "Vision–language–action model"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Vision–language–action_model"
wikipedia_categories: []
related: []
---

# Vision–language–action model

In robot learning, a vision–language–action model (VLA) is a class of multimodal foundation models that integrates vision, language and actions. Given an input image (or video) of the robot's surroundings and a text instruction, a VLA directly outputs low-level robot actions that can be executed to accomplish the requested task.
VLAs are generally constructed by fine-tuning a vision-language model (VLM) (i.e. a large language model extended with vision capabilities) on a large-scale dataset that pairs visual observation and language instructions with robot trajectories. These models combine a vision-language encoder (vision transformer), which translates an image observation and a natural language description into a distribution within a latent space, with an action decoder that transforms this representation into continuous output actions, directly executable on the robot.
The concept was pioneered in July 2023 by Google DeepMind with RT-2, a VLM adapted for end-to-end manipulation tasks, capable of unifying perception, reasoning and control.

## Related

*(no automatic links — see MOC)*

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Vision–language–action_model