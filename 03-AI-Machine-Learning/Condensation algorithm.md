---
title: "Condensation algorithm"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Condensation_algorithm"
wikipedia_categories: ["Computer vision"]
related: ["[[3D body scanning]]", "[[3D Morphable Model]]", "[[3D pose estimation]]", "[[3D reconstruction]]", "[[3D scanning]]", "[[3D selfie]]", "[[Active appearance model]]", "[[Active contour model]]", "[[Active shape model]]", "[[Active vision]]"]
---

# Condensation algorithm

The condensation algorithm (Conditional Density Propagation) is a computer vision algorithm. The principal application is to detect and track the contour of objects moving in a cluttered environment. Object tracking is one of the more basic and difficult aspects of computer vision and is generally a prerequisite to object recognition. Being able to identify which pixels in an image make up the contour of an object is a non-trivial problem. Condensation is a probabilistic algorithm that attempts to solve this problem.
The algorithm itself is described in detail by Isard and Blake in a publication in the International Journal of Computer Vision in 1998. One of the most interesting facets of the algorithm is that it does not compute on every pixel of the image. Rather, pixels to process are chosen at random, and only a subset of the pixels end up being processed. Multiple hypotheses about what is moving are supported naturally by the probabilistic nature of the approach. The evaluation functions come largely from previous work in the area and include many standard statistical approaches. The original part of this work is the application of particle filter estimation techniques.
The algorithm's creation was inspired by the inability of Kalman filtering to perform object tracking well in the presence of significant background clutter.  The presence of clutter tends to produce probability distributions for the object state which are multi-modal and therefore poorly modeled by the Kalman filter.  The condensation algorithm in its most general form requires no assumptions about the probability distributions of the object or measurements.

## Related

- [[3D body scanning]]
- [[3D Morphable Model]]
- [[3D pose estimation]]
- [[3D reconstruction]]
- [[3D scanning]]
- [[3D selfie]]
- [[Active appearance model]]
- [[Active contour model]]
- [[Active shape model]]
- [[Active vision]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Condensation_algorithm