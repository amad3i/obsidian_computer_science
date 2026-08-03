---
title: "Theil–Sen estimator"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Theil–Sen_estimator"
wikipedia_categories: ["Computational geometry", "Robust regression"]
related: ["[[3SUM]]", "[[Algorithmic Geometry]]", "[[Alpha shape]]", "[[Arrangement (space partition)]]", "[[Art gallery problem]]", "[[Art Gallery Theorems and Algorithms]]", "[[Badouel intersection algorithm]]", "[[Barrier resilience]]", "[[Bentley–Ottmann algorithm]]", "[[Beta skeleton]]"]
---

# Theil–Sen estimator

In non-parametric statistics, the Theil–Sen estimator is a method for robustly fitting a line to sample points in the plane (a form of simple linear regression) by choosing the median of the slopes of all lines through pairs of points. It has also been called Sen's slope estimator, slope selection, the single median method, the Kendall robust line-fit method, and the Kendall–Theil robust line. It is named after Henri Theil and Pranab K. Sen, who published papers on this method in 1950 and 1968 respectively, and after Maurice Kendall because of its relation to the Kendall tau rank correlation coefficient.
Theil–Sen regression has several advantages over Ordinary least squares regression. It is insensitive to outliers. It can be used for significance tests even when residuals are not normally distributed. It can be significantly more accurate than non-robust simple linear regression (least squares) for skewed and heteroskedastic data, and competes well against least squares even for normally distributed data in terms of statistical power. It has been called "the most popular nonparametric technique for estimating a linear trend". There are fast algorithms for efficiently computing the parameters.

## Related

- [[3SUM]]
- [[Algorithmic Geometry]]
- [[Alpha shape]]
- [[Arrangement (space partition)]]
- [[Art gallery problem]]
- [[Art Gallery Theorems and Algorithms]]
- [[Badouel intersection algorithm]]
- [[Barrier resilience]]
- [[Bentley–Ottmann algorithm]]
- [[Beta skeleton]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Theil–Sen_estimator