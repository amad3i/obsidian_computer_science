---
title: "Numeric precision in Microsoft Excel"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Numeric_precision_in_Microsoft_Excel"
wikipedia_categories: ["Microsoft software", "Numerical analysis", "Spreadsheet software"]
related: ["[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Adaptive step size]]", "[[Adjoint state method]]", "[[Affine arithmetic]]", "[[Applied element method]]", "[[Approximation]]", "[[Approximation error]]", "[[Approximation theory]]", "[[Arc-length method]]"]
---

# Numeric precision in Microsoft Excel

As with other spreadsheets, Microsoft Excel works only to limited accuracy because it retains only a certain number of figures to describe numbers (it has limited precision). With some exceptions regarding erroneous values, infinities, and denormalized numbers, Excel calculates in double-precision floating-point format from the IEEE 754 specification (besides numbers, Excel uses a few other data types).
Although Excel allows display of up to 30 decimal places, its precision for any specific number is no more than 15 significant figures, and calculations may have an accuracy that is even less due to five issues: round off, truncation, and binary storage, accumulation of the deviations of the operands in calculations, and worst, "catastrophic cancellation" at subtraction of values with similar magnitude. Standard floating-point error mitigation techniques apply.

## Related

- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Adaptive step size]]
- [[Adjoint state method]]
- [[Affine arithmetic]]
- [[Applied element method]]
- [[Approximation]]
- [[Approximation error]]
- [[Approximation theory]]
- [[Arc-length method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Numeric_precision_in_Microsoft_Excel