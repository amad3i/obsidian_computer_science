---
title: "Scale space implementation"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Scale_space_implementation"
wikipedia_categories: ["Computer vision", "Gaussian function", "Image processing"]
related: ["[[3D selfie]]", "[[Class activation mapping]]", "[[Color normalization]]", "[[Computer vision]]", "[[Contextual image classification]]", "[[Digital image processing]]", "[[Document mosaicing]]", "[[Dynamic texture]]", "[[Gaussian blur]]", "[[Image destriping]]"]
---

# Scale space implementation

In the areas of computer vision, image analysis and signal processing, the notion of scale-space representation is used for processing measurement data at multiple scales, and specifically enhance or suppress image features over different ranges of scale (see the article on scale space). A special type of scale-space representation is provided by the Gaussian scale space, where the image data in N dimensions is subjected to smoothing by Gaussian convolution. Most of the theory for Gaussian scale space deals with continuous images, whereas one when implementing this theory will have to face the fact that most measurement data are discrete. Hence, the theoretical problem arises concerning how to discretize the continuous theory while either preserving or well approximating the desirable theoretical properties that lead to the choice of the Gaussian kernel (see the article on scale-space axioms). This article describes basic approaches for this that have been developed in the literature, see also  for an in-depth treatment regarding the topic of approximating the Gaussian smoothing operation and the Gaussian derivative computations in scale-space theory, and  for a complementary treatment regarding hybrid discretization methods.

## Related

- [[3D selfie]]
- [[Class activation mapping]]
- [[Color normalization]]
- [[Computer vision]]
- [[Contextual image classification]]
- [[Digital image processing]]
- [[Document mosaicing]]
- [[Dynamic texture]]
- [[Gaussian blur]]
- [[Image destriping]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Scale_space_implementation