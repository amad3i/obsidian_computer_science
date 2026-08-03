---
title: "Point-set registration"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Point-set_registration"
wikipedia_categories: ["Computer vision", "Pattern matching", "Point (geometry)", "Robotics engineering"]
related: ["[[Normal distributions transform]]", "[[Superellipsoid]]", "[[Superquadrics]]", "[[3D body scanning]]", "[[3D Morphable Model]]", "[[3D pose estimation]]", "[[3D reconstruction]]", "[[3D scanning]]", "[[3D selfie]]", "[[Active appearance model]]"]
---

# Point-set registration

In computer vision, pattern recognition, and robotics, point-set registration, also known as point-cloud registration or scan matching, is the process of finding a spatial transformation (e.g., scaling, rotation and translation) that aligns two point clouds. The purpose of finding such a transformation includes merging multiple data sets into a globally consistent model (or coordinate frame), and mapping a new measurement to a known data set to identify features or to estimate its pose. Raw 3D point cloud data are typically obtained from Lidars and RGB-D cameras. 3D point clouds can also be generated from computer vision algorithms such as triangulation, bundle adjustment, and more recently, monocular image depth estimation using deep learning. For 2D point set registration used in image processing and feature-based image registration, a point set may be 2D pixel coordinates obtained by feature extraction from an image, for example corner detection. Point cloud registration has extensive applications in autonomous driving, motion estimation and 3D reconstruction, object detection and pose estimation, robotic manipulation, simultaneous localization and mapping (SLAM), panorama stitching, virtual and augmented reality, and medical imaging.
As a special case, registration of two point sets that only differ by a 3D rotation (i.e., there is no scaling and translation), is called the Wahba Problem and also related to the orthogonal procrustes problem.

## Related

- [[Normal distributions transform]]
- [[Superellipsoid]]
- [[Superquadrics]]
- [[3D body scanning]]
- [[3D Morphable Model]]
- [[3D pose estimation]]
- [[3D reconstruction]]
- [[3D scanning]]
- [[3D selfie]]
- [[Active appearance model]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Point-set_registration