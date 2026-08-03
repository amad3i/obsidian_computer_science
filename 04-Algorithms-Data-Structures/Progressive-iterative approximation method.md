---
title: "Progressive-iterative approximation method"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Progressive-iterative_approximation_method"
wikipedia_categories: ["Computational geometry", "Computer-aided design", "Computer graphics", "Curve fitting", "Geometric algorithms"]
related: ["[[Bentley–Ottmann algorithm]]", "[[Collision detection]]", "[[Euclidean shortest path]]", "[[Function representation]]", "[[Geometric design]]", "[[Geometric modeling]]", "[[Geometric primitive]]", "[[Hierarchical RBF]]", "[[Mesh generation]]", "[[Multiple line segment intersection]]"]
---

# Progressive-iterative approximation method

In mathematics, the progressive-iterative approximation method is an iterative method of data fitting with geometric meanings. Given a set of data points to be fitted, the method obtains a series of fitting curves (or surfaces) by iteratively updating the control points, and the limit curve (surface) can interpolate or approximate the given data points. It avoids solving a linear system of equations directly and allows flexibility in adding constraints during the iterative process. Therefore, it has been widely used in geometric design and related fields.
The study of the iterative method with geometric meaning can be traced back to the work of scholars such as Dongxu Qi and Carl de Boor in the 1970s. In 1975, Qi et al. developed and proved the "profit and loss" algorithm for uniform cubic B-spline curves, and in 1979, de Boor independently proposed this algorithm. In 2004, Hongwei Lin and coauthors proved that non-uniform cubic B-spline curves and surfaces have the "profit and loss" property. Later, in 2005, Lin et al. proved that the curves and surfaces with normalized and totally positive basis all have this property and named it progressive iterative approximation (PIA). In 2007, Maekawa et al. changed the algebraic distance in PIA to geometric distance and named it geometric interpolation (GI). In 2008, Cheng et al. extended it to subdivision surfaces and named the method progressive interpolation (PI). Since the iteration steps of the PIA, GI, and PI algorithms are similar and all have geometric meanings, they are collectively referred to as geometric iterative methods (GIM).
PIA is now extended to several common curves and surfaces in the geometric design field, including NURBS curves and surfaces, T-spline surfaces, and implicit curves and surfaces.

## Related

- [[Bentley–Ottmann algorithm]]
- [[Collision detection]]
- [[Euclidean shortest path]]
- [[Function representation]]
- [[Geometric design]]
- [[Geometric modeling]]
- [[Geometric primitive]]
- [[Hierarchical RBF]]
- [[Mesh generation]]
- [[Multiple line segment intersection]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Progressive-iterative_approximation_method