---
title: "Simple interactive object extraction"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Simple_interactive_object_extraction"
wikipedia_categories: ["Computer graphics", "Image segmentation"]
related: ["[[2D computer graphics]]", "[[3D computer graphics]]", "[[3D lookup table]]", "[[4D reconstruction]]", "[[9-slice scaling]]", "[[A-buffer]]", "[[ACM Transactions on Graphics]]", "[[Adaptive tile refresh]]", "[[Aphelion (software)]]", "[[Avizo (software)]]"]
---

# Simple interactive object extraction

Simple interactive object extraction (SIOX) is an algorithm for extracting foreground objects from color images and videos with very little user interaction. It has been implemented as "foreground selection" tool in the GIMP (since version 2.3.3), as part of the tracer tool in Inkscape (since 0.44pre3), and as function in ImageJ and Fiji (plug-in). Experimental implementations were also reported for Blender and Krita. Although the algorithm was originally designed for videos, virtually all implementations use SIOX primarily for still image segmentation. In fact, it is often said to be the current de facto standard for this task in the open-source world.
Initially, a free hand selection tool is used to specify the region of interest. It must contain all foreground objects to extract and as few background as possible. The pixels outside the region of interest form the sure background while the inner region define a superset of the foreground, i.e. the unknown region. A so-called foreground brush is then used to mark representative foreground regions. The algorithm outputs a selection mask. The selection can be refined by either adding further foreground markings or by adding background markings using the background brush.
Technically, the algorithm performs the following steps: 

Create a set of representative colors for sure foreground and sure background, the so-called color signatures.
Assign all image points to foreground or background by a weighted nearest neighbor search in the color signatures.
Apply some standard image processing operations like erode, dilate, and blur to remove artifacts.
Find the connected foreground components that are either large enough or marked by the user.
For video segmentation the sure background and sure foreground regions are learned from motion statistics. SIOX also features tools that allow sub-pixel accurate refinement of edges and high texture areas, the so-called "detail refinement brushes".
As with all segmentation algorithms, there are always pictures where the algorithm does not yield perfect results. The most critical drawback of SIOX is the color dependence. Although many photos are well-separable by color, the algorithm cannot deal with camouflage. If the foreground and background share many identical shades of similar colors, the algorithm might give a result with parts missing or incorrectly classified foreground. SIOX performs about equally well on different benchmarks compared to graph-based segmentation methods, such as Grabcut. SIOX is, however, more noise robust and can therefore also be used for the segmentation of videos. Graph-based segmentation methods search for a minimum cut and therefore tend to not perform optimally with complex structures.
The algorithm has initially been developed at the department of computer science at Freie Universitaet Berlin. The main developer, Gerald Friedland, is now faculty at the EECS department of the University of California at Berkeley and also a Principal Data Scientist at Lawrence Livermore National Lab. He continues to support the development through mentoring, e.g. in the Google Summer of Code.

## Related

- [[2D computer graphics]]
- [[3D computer graphics]]
- [[3D lookup table]]
- [[4D reconstruction]]
- [[9-slice scaling]]
- [[A-buffer]]
- [[ACM Transactions on Graphics]]
- [[Adaptive tile refresh]]
- [[Aphelion (software)]]
- [[Avizo (software)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Simple_interactive_object_extraction