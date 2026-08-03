---
title: "Significant figures"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Significant_figures"
wikipedia_categories: ["Arithmetic", "Numerical analysis"]
related: ["[[False precision]]", "[[Grossone]]", "[[Interval arithmetic]]", "[[Interval contractor]]", "[[2Sum]]", "[[Abramowitz and Stegun]]", "[[Ackermann function]]", "[[Adaptive step size]]", "[[Adding machine]]", "[[Adjoint state method]]"]
---

# Significant figures

Significant figures, also referred to as significant digits, are specific digits within a number that is written in positional notation that carry both reliability and necessity in conveying a particular quantity. When presenting the outcome of a measurement (such as length, pressure, volume, or mass), if the number of digits exceeds what the measurement instrument can resolve, only the digits that are determined by the resolution are dependable and therefore considered significant.
For instance, if a length measurement yields 114.8 millimetres (mm), using a ruler with the smallest interval between marks at 1 mm, the first three digits (1, 1, and 4, representing 114 mm) are certain and constitute significant figures. Further, digits that are uncertain yet meaningful are also included in the significant figures. In this example, the last digit (8, contributing 0.8 mm) is likewise considered significant despite its uncertainty. Therefore, this measurement contains four significant figures.
Another example involves a volume measurement of 2.98 litres (L) with an uncertainty of ± 0.05 L. The actual volume falls between 2.93 L and 3.03 L. Even if certain digits are not completely known, they are still significant if they are meaningful, as they indicate the actual volume within an acceptable range of uncertainty. In this case, the actual volume might be 2.94 L or possibly 3.02 L, so all three digits are considered significant. Thus, there are three significant figures in this example.
The following types of digits are not considered significant:

Leading zeros. For instance, 013 kg has two significant figures—1 and 3—while the leading zero is insignificant since it does not impact the mass indication; 013 kg is equivalent to 13 kg, rendering the zero unnecessary. Similarly, in the case of 0.056 m, there are two insignificant leading zeros since 0.056 m is the same as 56 mm, thus the leading zeros do not contribute to the length indication.
Trailing zeros when they serve as placeholders. In the measurement 1500 m, when the measurement resolution is 100 m, the trailing zeros are insignificant as they simply stand for the tens and ones places. In this instance, 1500 m indicates the length is approximately 1500 m rather than an exact value of 1500 m.
Spurious digits that arise from calculations resulting in a higher precision than the original data or a measurement reported with greater precision than the instrument's resolution.
A zero after a decimal (e.g., 1.0) is significant, and care should be used when appending such a decimal of zero. Thus, in the case of 1.0, there are two significant figures, whereas 1 (without a decimal) has one significant figure.
Among a number's significant digits, the most significant digit is the one with the greatest exponent value (the leftmost significant digit/figure), while the least significant digit is the one with the lowest exponent value (the rightmost significant digit/figure). For example, in the number "123" the "1" is the most significant digit, representing hundreds (102), while the "3" is the least significant digit, representing ones (100).
To avoid conveying a misleading level of precision, numbers are often rounded. For instance, it would create false precision to present a measurement as 12345.25 g when the measuring instrument only provides accuracy to the nearest gram. In this case, the significant figures are the first five digits (1, 2, 3, 4, and 5) from the leftmost digit, and the number should be rounded to these significant figures, resulting in 12345 g as the accurate value. The rounding error (in this example, 0.25 g) approximates the numerical resolution or precision. Numbers can also be rounded for simplicity, not necessarily to indicate measurement precision, such as for the sake of expediency in news broadcasts.
Significance arithmetic encompasses a set of approximate rules for preserving significance through calculations. More advanced scientific rules are known as the propagation of uncertainty.
Radix 10 (base-10, decimal numbers) is assumed in the following. (See Unit in the last place for extending these concepts to other bases.)

## Related

- [[False precision]]
- [[Grossone]]
- [[Interval arithmetic]]
- [[Interval contractor]]
- [[2Sum]]
- [[Abramowitz and Stegun]]
- [[Ackermann function]]
- [[Adaptive step size]]
- [[Adding machine]]
- [[Adjoint state method]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Significant_figures