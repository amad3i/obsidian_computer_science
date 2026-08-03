---
title: "Neighborhood operation"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Neighborhood_operation"
wikipedia_categories: ["Computer vision", "Image processing"]
related: ["[[3D selfie]]", "[[Class activation mapping]]", "[[Color normalization]]", "[[Computer vision]]", "[[Contextual image classification]]", "[[Digital image processing]]", "[[Document mosaicing]]", "[[Dynamic texture]]", "[[Image destriping]]", "[[Image formation]]"]
---

# Neighborhood operation

In computer vision and image processing a neighborhood operation is a commonly used class of computations on image data which implies that it is processed according to the following pseudo code:

Visit each point p in the image data and do {
    N = a neighborhood or region of the image data around the point p
    result(p) = f(N)
}

This general procedure can be applied to image data of arbitrary dimensionality.  Also, the image data on which the operation is applied does not have to be defined in terms of intensity or color, it can be any type of information which is organized as a function of spatial (and possibly temporal) variables in p.
The result of applying a neighborhood operation on an image is again something which can be interpreted as an image, it has the same dimension as the original data.  The value at each image point, however, does not have to be directly related to intensity or color.  Instead it is an element in the range of the function f, which can be of arbitrary type.
Normally the neighborhood N is of fixed size and is a square (or a cube, depending on the dimensionality of the image data) centered on the point p.  Also the function f is fixed, but may in some cases have parameters which can vary with p, see below.
In the simplest case, the neighborhood N may be only a single point.  This type of operation is often referred to as a point-wise operation.

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

- Wikipedia: https://en.wikipedia.org/wiki/Neighborhood_operation