---
title: "Active contour model"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Active_contour_model"
wikipedia_categories: ["Computer vision"]
related: ["[[3D body scanning]]", "[[3D Morphable Model]]", "[[3D pose estimation]]", "[[3D reconstruction]]", "[[3D scanning]]", "[[3D selfie]]", "[[Active appearance model]]", "[[Active shape model]]", "[[Active vision]]", "[[Alignments of random points]]"]
---

# Active contour model

Active contour model, also called snakes, is a framework in computer vision introduced by Michael Kass, Andrew Witkin, and Demetri Terzopoulos for delineating an object outline from a possibly noisy 2D image. The snakes model is popular in computer vision, and snakes are widely used in applications like object tracking, shape recognition, segmentation, edge detection and stereo matching.
A snake is an energy minimizing, deformable spline influenced by constraint and image forces that pull it towards object contours and internal forces that resist deformation. Snakes may be understood as a special case of the general technique of matching a deformable model to an image by means of energy minimization. In two dimensions, the active shape model represents a discrete version of this approach, taking advantage of the point distribution model to restrict the shape range to an explicit domain learnt from a training set.

Snakes do not solve the entire problem of finding contours in images, since the method requires knowledge of the desired contour shape beforehand. Rather, they depend on other mechanisms such as interaction with a user, interaction with some higher level image understanding process, or information from image data adjacent in time or space.

## Related

- [[3D body scanning]]
- [[3D Morphable Model]]
- [[3D pose estimation]]
- [[3D reconstruction]]
- [[3D scanning]]
- [[3D selfie]]
- [[Active appearance model]]
- [[Active shape model]]
- [[Active vision]]
- [[Alignments of random points]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Active_contour_model