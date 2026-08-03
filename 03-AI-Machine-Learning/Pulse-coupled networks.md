---
title: "Pulse-coupled networks"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Pulse-coupled_networks"
wikipedia_categories: ["Artificial neural networks", "Image processing"]
related: ["[[3D selfie]]", "[[A Logical Calculus of the Ideas Immanent in Nervous Activity]]", "[[Abel transform]]", "[[ActionShot]]", "[[Activation function]]", "[[Acutance]]", "[[ADALINE]]", "[[Adaptive histogram equalization]]", "[[Adaptive neuro fuzzy inference system]]", "[[Adaptive resonance theory]]"]
---

# Pulse-coupled networks

Pulse-coupled networks or pulse-coupled neural networks (PCNNs) are neural models proposed by modeling a cat's visual cortex, and developed for high-performance biomimetic image processing.
In 1989, Eckhorn introduced a neural model to emulate the mechanism of cat's visual cortex. The Eckhorn model provided a simple and effective tool for studying small mammal’s visual cortex, and was soon recognized as having significant application potential in image processing.
In 1994, Johnson adapted the Eckhorn model to an image processing algorithm, calling this algorithm a pulse-coupled neural network.
The basic property of the Eckhorn's linking-field model (LFM) is the coupling term.  LFM is a modulation of the primary input by a biased offset factor driven by the linking input.  These drive a threshold variable that decays from an initial high value.  When the threshold drops below zero it is reset to a high value and the process starts over.  This is different than the standard integrate-and-fire neural model, which accumulates the input until it passes an upper limit and effectively "shorts out" to cause the pulse.
LFM uses this difference to sustain pulse bursts, something the standard model does not do on a single neuron level. It is valuable to understand, however, that a detailed analysis of the standard model must include a shunting term, due to the floating voltages level in the dendritic compartment(s), and in turn this causes an elegant multiple modulation effect that enables a true higher-order network (HON).
A PCNN is a two-dimensional neural network. Each neuron in the network corresponds to one pixel in an input image, receiving its corresponding pixel's color information (e.g. intensity) as an external stimulus. Each neuron also connects with its neighboring neurons, receiving local stimuli from them. The external and local stimuli are combined in an internal activation system, which accumulates the stimuli until it exceeds a dynamic threshold, resulting in a pulse output. Through iterative computation, PCNN neurons produce temporal series of pulse outputs. The temporal series of pulse outputs contain information of input images and can be used for various image processing applications, such as image segmentation and feature generation. Compared with conventional image processing means, PCNNs have several significant merits, including robustness against noise, independence of geometric variations in input patterns, capability of bridging minor intensity variations in input patterns, etc.
A simplified PCNN called a spiking cortical model was developed in 2009.

## Related

- [[3D selfie]]
- [[A Logical Calculus of the Ideas Immanent in Nervous Activity]]
- [[Abel transform]]
- [[ActionShot]]
- [[Activation function]]
- [[Acutance]]
- [[ADALINE]]
- [[Adaptive histogram equalization]]
- [[Adaptive neuro fuzzy inference system]]
- [[Adaptive resonance theory]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Pulse-coupled_networks