---
title: "Chebyshev pseudospectral method"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Chebyshev_pseudospectral_method"
wikipedia_categories: ["Control theory", "Numerical analysis", "Optimal control"]
related: ["[[Bellman pseudospectral method]]", "[[Flat pseudospectral method]]", "[[Legendre pseudospectral method]]", "[[Pseudospectral knotting method]]", "[[Ross' π lemma]]", "[[Ross–Fahroo lemma]]", "[[Ross–Fahroo pseudospectral method]]", "[[Discretization]]", "[[Gap metric]]", "[[Microgrid]]"]
---

# Chebyshev pseudospectral method

The Chebyshev pseudospectral method for optimal control problems is based on Chebyshev polynomials of the first kind. It is part of the larger theory of pseudospectral optimal control, a term coined by Ross. Unlike the Legendre pseudospectral method, the Chebyshev pseudospectral (PS) method does not immediately offer high-accuracy quadrature solutions. Consequently, two different versions of the method have been proposed: one by Elnagar et al., and another by Fahroo and Ross.  The two versions differ in their quadrature techniques.  The Fahroo–Ross method is more commonly used today due to the ease in implementation of the Clenshaw–Curtis quadrature technique (in contrast to Elnagar–Kazemi's cell-averaging method). In 2008, Trefethen showed that the Clenshaw–Curtis method was nearly as accurate as Gauss quadrature.
  This breakthrough result opened the door for a covector mapping theorem for Chebyshev PS methods.  A complete mathematical theory for Chebyshev PS methods was finally developed in 2009 by Gong, Ross and Fahroo.

## Related

- [[Bellman pseudospectral method]]
- [[Flat pseudospectral method]]
- [[Legendre pseudospectral method]]
- [[Pseudospectral knotting method]]
- [[Ross' π lemma]]
- [[Ross–Fahroo lemma]]
- [[Ross–Fahroo pseudospectral method]]
- [[Discretization]]
- [[Gap metric]]
- [[Microgrid]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Chebyshev_pseudospectral_method