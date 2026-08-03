---
title: "Signal separation"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Signal_separation"
wikipedia_categories: ["Digital signal processing", "Speech processing"]
related: ["[[2D adaptive filters]]", "[[2D Z-transform]]", "[[Adaptive equalizer]]", "[[Adaptive filter]]", "[[Adaptive predictive coding]]", "[[Adaptive-additive algorithm]]", "[[Adjoint filter]]", "[[Advanced process control]]", "[[Aliasing]]", "[[All-pass filter]]"]
---

# Signal separation

Source separation, blind signal separation (BSS) or blind source separation, is the separation of a set of source signals from a set of mixed signals, without the aid of information (or with very little information) about the source signals or the mixing process. It is most commonly applied in digital signal processing and involves the analysis of mixtures of signals; the objective is to recover the original component signals from a mixture signal. The classical example of a source separation problem is the cocktail party problem, where a number of people are talking simultaneously in a room (for example, at a cocktail party), and a listener is trying to follow one of the discussions. The human brain can handle this sort of auditory source separation problem, but it is a difficult problem in digital signal processing.
This problem is in general highly underdetermined, but useful solutions can be derived under a surprising variety of conditions. Much of the early literature in this field focuses on the separation of temporal signals such as audio. However, blind signal separation is now routinely performed on multidimensional data, such as images and tensors, which may involve no time dimension whatsoever.  
Several approaches have been proposed for the solution of this problem but development is currently still very much in progress. Some of the more successful approaches are principal components analysis and independent component analysis, which work well when there are no delays or echoes present; that is, the problem is simplified a great deal. The field of computational auditory scene analysis attempts to achieve auditory source separation using an approach that is based on human hearing.
The human brain must also solve this problem in real time. In human perception this ability is commonly referred to as auditory scene analysis or the cocktail party effect.

## Related

- [[2D adaptive filters]]
- [[2D Z-transform]]
- [[Adaptive equalizer]]
- [[Adaptive filter]]
- [[Adaptive predictive coding]]
- [[Adaptive-additive algorithm]]
- [[Adjoint filter]]
- [[Advanced process control]]
- [[Aliasing]]
- [[All-pass filter]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Signal_separation