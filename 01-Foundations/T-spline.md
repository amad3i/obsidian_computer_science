---
title: "T-spline"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/T-spline"
wikipedia_categories: ["Computer-aided design", "Splines (mathematics)"]
related: ["[[Non-uniform rational B-spline]]", "[[Plasticity (software)]]", "[[2D geometric model]]", "[[3D Content Retrieval]]", "[[3D floor plan]]", "[[3D Systems]]", "[[AgcXML]]", "[[Algorithms-Aided Design]]", "[[Architectural animation]]", "[[Architectural geometry]]"]
---

# T-spline

In computer graphics, a T-spline is a mathematical model for defining freeform surfaces. A T-spline surface is a type of surface defined by a network of control points where a row of control points is allowed to terminate without traversing the entire surface. The control net at a terminated row resembles the letter "T".
B-splines are a type of curve widely used in CAD modeling. They consist of a list of control points (a list of (X, Y) or (X, Y, Z) coordinates) and a knot vector (a list increasing numbers, usually between 0 and 1). In order to perfectly represent circles and other conic sections, a weight component is often added, which extends B-splines to rational B-splines, commonly called NURBS. A NURBS curve represents a 1D perfectly smooth curve in 2D or 3D space.
To represent a three-dimensional solid object, or a patch of one, B-spline or NURBS curves are extended to surfaces. These surfaces consist of a rectangular grid of control points, called a control grid or control net, and two knot vectors, commonly called U and V. During editing, it is possible to insert a new control point into a curve without changing the shape of the curve. This is useful to allow a user to adjust this new control point, as opposed to only being able to adjust the existing control points. However, because the control grid of a B-spline or NURBS surface has to be rectangular, it is only possible to insert an entire row or column of new control points.
T-splines are an enhancement of NURBS surfaces. They allow control points to be added to the control grid without inserting an entire new row or column. Instead, the new control points can terminate a row or column, which creates a "T" shape in the otherwise rectangular control grid. This is accomplished by assigning a knot vector to each individual control point, and creating some rules around how control points are added or removed.
Modeling surfaces with T-splines can reduce the number of control points in comparison to NURBS surfaces and make pieces easier to merge, but increases the book-keeping effort to keep track of the irregular connectivity. T-splines can be converted into NURBS surfaces, by knot insertion, and NURBS can be represented as T-splines without T's or by removing knots. T-splines can therefore, in theory, do everything that NURBS can do. In practice, an enormous amount of programming was required to make NURBS work as well as they do, and creating the equivalent T-spline functionality would require similar effort. To smoothly join at points where more than three surface pieces meet, T-splines have been combined with geometrically continuous constructions of degree 3 by 3 (bi-cubic) and, more recently, of degree 4 by 4 (bi-quartic).
Subdivision surfaces, NURBS surfaces, and polygon meshes are alternative technologies. Subdivision surfaces, as well as T-spline and NURBS surfaces with the addition of geometrically continuous constructions, can represent everywhere-smooth surfaces of any connectivity and topology, such as holes, branches, and handles. However, none of T-splines, subdivision surfaces, or NURBS surfaces can always accurately represent the (exact, algebraic) intersection of two surfaces within the same surface representation. Polygon meshes can represent exact intersections but lack the shape quality required in industrial design. Subdivision surfaces are widely adopted in the animation industry.  Pixar's variant of the subdivision surfaces has the advantage of edge weights. T-splines do not yet have edge weights.
T-splines were initially defined in 2003. In 2007 the U.S. patent office granted patent number 7,274,364 for technologies related to T-splines. T-Splines, Inc. was founded in 2004 to commercialize the technologies and acquired by Autodesk, Inc. in 2011. The T-spline patent, US patent 7,274,364, expired in 2024.

## Related

- [[Non-uniform rational B-spline]]
- [[Plasticity (software)]]
- [[2D geometric model]]
- [[3D Content Retrieval]]
- [[3D floor plan]]
- [[3D Systems]]
- [[AgcXML]]
- [[Algorithms-Aided Design]]
- [[Architectural animation]]
- [[Architectural geometry]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/T-spline