---
title: "Randomized Hough transform"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Randomized_Hough_transform"
wikipedia_categories: ["Computer vision", "Image processing"]
related: ["[[3D selfie]]", "[[Class activation mapping]]", "[[Color normalization]]", "[[Computer vision]]", "[[Contextual image classification]]", "[[Digital image processing]]", "[[Document mosaicing]]", "[[Dynamic texture]]", "[[Image destriping]]", "[[Image formation]]"]
---

# Randomized Hough transform

Hough transforms are techniques for object detection, a critical step in many implementations of computer vision, or data mining from images. Specifically, the Randomized Hough transform is a probabilistic variant to the classical Hough transform, and is commonly used to detect curves (straight line, circle, ellipse, etc.) The basic idea of Hough transform (HT) is to implement a voting procedure for all potential curves in the image, and at the termination of the algorithm, curves that do exist in the image will have relatively high voting scores. Randomized Hough transform (RHT) is different from HT in that it tries to avoid conducting the computationally expensive voting process for every nonzero pixel in the image by taking advantage of the geometric properties of analytical curves, and thus improve the time efficiency and reduce the storage requirement of the original algorithm.

## Related

- [[3D selfie]]
- [[Class activation mapping]]
- [[Color normalization]]
- [[Computer vision]]
- [[Contextual image classification]]
- [[Digital image processing]]
- [[Document mosaicing]]
- [[Dynamic texture]]
- [[Image destriping]]
- [[Image formation]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Randomized_Hough_transform