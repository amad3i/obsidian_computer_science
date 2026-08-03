---
title: "Z-order curve"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Z-order_curve"
wikipedia_categories: ["Database algorithms", "Database index techniques", "Fractal curves", "Geometric data structures", "Linear algebra"]
related: ["[[3D projection]]", "[[Absolutely convex set]]", "[[Adjugate matrix]]", "[[Affine space]]", "[[Amitsur–Levitzki theorem]]", "[[Angles between flats]]", "[[Annihilating polynomial]]", "[[Antilinear map]]", "[[Antiunitary operator]]", "[[Asymmetric norm]]"]
---

# Z-order curve

In mathematical analysis and computer science, functions which are Z-order, Lebesgue curve, Morton space-filling curve, Morton order or Morton code map multidimensional data to one dimension while preserving locality of the data points (two points close together in multidimensions with high probability lie also close together in Morton order). It is named in France after Henri Lebesgue, who studied it in 1904, and named in the United States after Guy Macdonald Morton, who first applied the order to file sequencing in 1966. The z-value of a point in multidimensions is simply calculated by bit interleaving the binary representations of its coordinate values. However, when querying a multidimensional search range in these data, using binary search is not really efficient: It is necessary for calculating, from a point encountered in the data structure, the next possible Z-value which is in the multidimensional search range, called BIGMIN. The BIGMIN problem has first been stated and its solution shown by Tropf and Herzog in 1981. Once the data are sorted by bit interleaving, any one-dimensional data structure can be used, such as simple one dimensional arrays, binary search trees, B-trees, skip lists or (with low significant bits truncated) hash tables. The resulting ordering can equivalently be described as the order one would get from a depth-first traversal of a quadtree or octree.

## Related

- [[3D projection]]
- [[Absolutely convex set]]
- [[Adjugate matrix]]
- [[Affine space]]
- [[Amitsur–Levitzki theorem]]
- [[Angles between flats]]
- [[Annihilating polynomial]]
- [[Antilinear map]]
- [[Antiunitary operator]]
- [[Asymmetric norm]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Z-order_curve