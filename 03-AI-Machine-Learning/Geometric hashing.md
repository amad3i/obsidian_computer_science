---
title: "Geometric hashing"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Geometric_hashing"
wikipedia_categories: ["Computer vision", "Geometric data structures", "Search algorithms"]
related: ["[[Fractional cascading]]", "[[(1+ε)-approximate nearest neighbor search]]", "[[3D body scanning]]", "[[3D Morphable Model]]", "[[3D pose estimation]]", "[[3D reconstruction]]", "[[3D scanning]]", "[[3D selfie]]", "[[A- search algorithm]]", "[[Active appearance model]]"]
---

# Geometric hashing

In computer science, geometric hashing is a method for efficiently finding two-dimensional objects represented by discrete points that have undergone an affine transformation, though extensions exist to other object representations and transformations. In an off-line step, the objects are encoded by treating each pair of points as a geometric basis. The remaining points can be represented in an invariant fashion with respect to this basis using two parameters. For each point, its quantized transformed coordinates are stored in the hash table as a key, and indices of the basis points as a value. Then a new pair of basis points is selected, and the process is repeated. In the on-line (recognition) step, randomly selected pairs of data points are considered as candidate bases. For each candidate basis, the remaining data points are encoded according to the basis and possible correspondences from the object are found in the previously constructed table. The candidate basis is accepted if a sufficiently large number of the data points index a consistent object basis.
Geometric hashing was originally suggested in computer vision for object recognition in 2D and 3D, but later was applied to different problems such as structural alignment of proteins.

## Related

- [[Fractional cascading]]
- [[(1+ε)-approximate nearest neighbor search]]
- [[3D body scanning]]
- [[3D Morphable Model]]
- [[3D pose estimation]]
- [[3D reconstruction]]
- [[3D scanning]]
- [[3D selfie]]
- [[A- search algorithm]]
- [[Active appearance model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Geometric_hashing