---
title: "Normal distributions transform"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Normal_distributions_transform"
wikipedia_categories: ["Computer vision", "Pattern matching"]
related: ["[[Point-set registration]]", "[[3D body scanning]]", "[[3D Morphable Model]]", "[[3D pose estimation]]", "[[3D reconstruction]]", "[[3D scanning]]", "[[3D selfie]]", "[[Active appearance model]]", "[[Active contour model]]", "[[Active shape model]]"]
---

# Normal distributions transform

The normal distributions transform (NDT) is a point cloud registration algorithm introduced by Peter Biber and Wolfgang Straßer in 2003, while working at University of Tübingen.
The algorithm registers two point clouds by first associating a piecewise normal distribution to the first point cloud, that gives the probability of sampling a point belonging to the cloud at a given spatial coordinate, and then finding a transform that maps the second point cloud to the first by maximising the likelihood of the second point cloud on such distribution as a function of the transform parameters.
Originally introduced for 2D point cloud map matching in simultaneous localization and mapping (SLAM) and relative position tracking, the algorithm was extended to 3D point clouds and has wide applications in computer vision and robotics. NDT is very fast and accurate, making it suitable for application to large scale data, but it is also sensitive to initialisation, requiring a sufficiently accurate initial guess, and for this reason it is typically used in a coarse-to-fine alignment strategy.

## Related

- [[Point-set registration]]
- [[3D body scanning]]
- [[3D Morphable Model]]
- [[3D pose estimation]]
- [[3D reconstruction]]
- [[3D scanning]]
- [[3D selfie]]
- [[Active appearance model]]
- [[Active contour model]]
- [[Active shape model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Normal_distributions_transform