---
title: "3D reconstruction from multiple images"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/3D_reconstruction_from_multiple_images"
wikipedia_categories: ["3D imaging", "Applications of computer vision"]
related: ["[[3D selfie]]", "[[Image-based modeling and rendering]]", "[[View synthesis]]", "[[3D body scanning]]", "[[3D computer graphics]]", "[[3D modeling]]", "[[3D projection]]", "[[3D reconstruction]]", "[[3D scanning]]", "[[3D tracking]]"]
---

# 3D reconstruction from multiple images

3D reconstruction from multiple images is the creation of three-dimensional models from a set of images. It is the reverse process of obtaining 2D images from 3D scenes.
The essence of an image is to project a 3D scene onto a 2D plane, during which process, the depth is lost. The 3D point corresponding to a specific image point is constrained to be on the line of sight. From a single image, it is impossible to determine which point on this line corresponds to the image point. If two images are available, then the position of a 3D point can be found as the intersection of the two projection rays. This process is referred to as triangulation. The key for this process is the relations between multiple views, which convey that the corresponding sets of points must contain some structure, and that this structure is related to the poses and the calibration of the camera.
In recent decades, there has been a significant demand for 3D content in application to computer graphics, virtual reality and communication, which also demanded a change in the required tools and devices in creating 3D. Most existing systems for constructing 3D models are built around specialized hardware (e.g. stereo rigs), resulting in a high cost. This gap stimulates the use of digital imaging facilities (like cameras). An early method was proposed by Tomasi and Kanade, in which they used an affine factorization approach to extract 3D from image sequences. However, the assumption of orthographic projection is a significant limitation of this system.

## Related

- [[3D selfie]]
- [[Image-based modeling and rendering]]
- [[View synthesis]]
- [[3D body scanning]]
- [[3D computer graphics]]
- [[3D modeling]]
- [[3D projection]]
- [[3D reconstruction]]
- [[3D scanning]]
- [[3D tracking]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/3D_reconstruction_from_multiple_images