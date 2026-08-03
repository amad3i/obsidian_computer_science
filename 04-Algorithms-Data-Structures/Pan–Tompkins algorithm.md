---
title: "Pan–Tompkins algorithm"
tags: ["cs", "algorithms-data-structures", "intermediate"]
domain: Algorithms & Data Structures
level: intermediate
source: "https://en.wikipedia.org/wiki/Pan–Tompkins_algorithm"
wikipedia_categories: ["Algorithms", "Cardiac electrophysiology"]
related: ["[[Adaptive algorithm]]", "[[Algorism]]", "[[Algorithm]]", "[[Algorithm characterizations]]", "[[Algorithm engineering]]", "[[Algorithm IMED]]", "[[Algorithmic amplification]]", "[[Algorithmic logic]]", "[[Algorithmic management]]", "[[Algorithmic mechanism design]]"]
---

# Pan–Tompkins algorithm

The Pan–Tompkins algorithm is commonly used to detect QRS complexes in electrocardiographic signals (ECG). The QRS complex represents the ventricular depolarization and the main spike visible in an ECG signal (see figure). This feature makes it particularly suitable for measuring heart rate, the first way to assess the heart health state. In the first derivation of Einthoven of a physiological heart, the QRS complex is composed by a downward deflection (Q wave), a high upward deflection (R wave) and a final downward deflection (S wave).
The Pan–Tompkins algorithm applies a series of filters to highlight the frequency content of this rapid heart depolarization and removes the background noise. Then, it squares the signal to amplify the QRS contribution, which makes identifying the QRS complex more straightforward. Finally, it applies adaptive thresholds to detect the peaks of the filtered signal. The algorithm was proposed by Jiapu Pan and Willis J. Tompkins in 1985, in the journal IEEE Transactions on Biomedical Engineering. The performance of the method was tested on an annotated arrhythmia database (MIT/BIH) and evaluated also in presence of noise. Pan and Tompkins reported that the 99.3 percent of QRS complexes was correctly detected.

## Related

- [[Adaptive algorithm]]
- [[Algorism]]
- [[Algorithm]]
- [[Algorithm characterizations]]
- [[Algorithm engineering]]
- [[Algorithm IMED]]
- [[Algorithmic amplification]]
- [[Algorithmic logic]]
- [[Algorithmic management]]
- [[Algorithmic mechanism design]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Pan–Tompkins_algorithm