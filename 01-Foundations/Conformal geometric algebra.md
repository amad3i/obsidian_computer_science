---
title: "Conformal geometric algebra"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Conformal_geometric_algebra"
wikipedia_categories: ["Computational geometry", "Conformal geometry", "Geometric algebra", "Inversive geometry"]
related: ["[[3SUM]]", "[[Algorithmic Geometry]]", "[[Alpha shape]]", "[[Arrangement (space partition)]]", "[[Art gallery problem]]", "[[Art Gallery Theorems and Algorithms]]", "[[Badouel intersection algorithm]]", "[[Barrier resilience]]", "[[Bentley–Ottmann algorithm]]", "[[Beta skeleton]]"]
---

# Conformal geometric algebra

Conformal geometric algebra (CGA) is the geometric algebra constructed over the resultant space of a map from points in an n-dimensional base space Rp,q to null vectors in Rp+1,q+1.  This allows operations on the base space, including reflections, rotations and translations to be represented using versors of the geometric algebra; and it is found that points, lines, planes, circles and spheres gain particularly natural and computationally amenable representations.
The effect of the mapping is that generalized (i.e. including zero curvature) k-spheres in the base space map onto (k + 2)-blades, and so that the effect of a translation (or any conformal mapping) of the base space corresponds to a rotation in the higher-dimensional space.  In the algebra of this space, based on the geometric product of vectors, such transformations correspond to the algebra's characteristic sandwich operations, similar to the use of quaternions for spatial rotation in 3D, which combine very efficiently.  A consequence of rotors representing transformations is that the representations of spheres, planes, circles and other geometrical objects, and equations connecting them, all transform covariantly.  A geometric object (a k-sphere) can be synthesized as the wedge product of k + 2 linearly independent vectors representing points on the object; conversely, the object can be decomposed as the repeated wedge product of vectors representing k + 2 distinct points in its surface.  Some intersection operations also acquire a tidy algebraic form: for example, for the Euclidean base space R3, applying the wedge product to the dual of the tetravectors representing two spheres produces the dual of the trivector representation of their circle of intersection.
As this algebraic structure lends itself directly to effective computation, it facilitates exploration of the classical methods of projective geometry and inversive geometry in a concrete, easy-to-manipulate setting.  It has also been used as an efficient structure to represent and facilitate calculations in screw theory. CGA has particularly been applied in connection with the projective mapping of the everyday Euclidean space R3 into a five-dimensional vector space R4,1, which has been investigated for applications in robotics and computer vision.  It can be applied generally to any pseudo-Euclidean space – for example, Minkowski space R3,1 to the space R4,2.

## Related

- [[3SUM]]
- [[Algorithmic Geometry]]
- [[Alpha shape]]
- [[Arrangement (space partition)]]
- [[Art gallery problem]]
- [[Art Gallery Theorems and Algorithms]]
- [[Badouel intersection algorithm]]
- [[Barrier resilience]]
- [[Bentley–Ottmann algorithm]]
- [[Beta skeleton]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Conformal_geometric_algebra