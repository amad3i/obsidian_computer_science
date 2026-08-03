---
title: "Total operating characteristic"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Total_operating_characteristic"
wikipedia_categories: ["Biostatistics", "Boolean algebra", "Data mining", "Detection theory", "Statistical classification", "Summary statistics for contingency tables"]
related: ["[[Receiver operating characteristic]]", "[[Phi coefficient]]", "[[Sensitivity and specificity]]", "[[1-in-3-SAT]]", "[[Action model learning]]", "[[Adamic–Adar index]]", "[[Affinity analysis]]", "[[Agent mining]]", "[[AMiner (database)]]", "[[Analysis of Boolean functions]]"]
---

# Total operating characteristic

The total operating characteristic (TOC) is a statistical method to compare a Boolean variable versus a rank variable. TOC can measure the ability of an index variable to diagnose either presence or absence of a characteristic. The diagnosis of presence or absence depends on whether the value of the index is above a threshold. TOC considers multiple possible thresholds. Each threshold generates a two-by-two contingency table, which contains four entries: hits, misses, false alarms, and correct rejections.
The receiver operating characteristic (ROC) also characterizes diagnostic ability, although ROC reveals less information than the TOC. For each threshold, ROC reveals two ratios, hits/(hits + misses) and false alarms/(false alarms + correct rejections), while TOC shows the total information in the contingency table for each threshold. The TOC method reveals all of the information that the ROC method provides, plus additional important information that ROC does not reveal, i.e. the size of every entry in the contingency table for each threshold. TOC also provides the popular area under the curve (AUC) of the ROC.
TOC is applicable to measure diagnostic ability in many fields including but not limited to: land change science, medical imaging, weather forecasting, remote sensing, and materials testing.

## Related

- [[Receiver operating characteristic]]
- [[Phi coefficient]]
- [[Sensitivity and specificity]]
- [[1-in-3-SAT]]
- [[Action model learning]]
- [[Adamic–Adar index]]
- [[Affinity analysis]]
- [[Agent mining]]
- [[AMiner (database)]]
- [[Analysis of Boolean functions]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Total_operating_characteristic