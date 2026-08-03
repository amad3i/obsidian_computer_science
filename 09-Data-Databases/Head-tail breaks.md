---
title: "Head/tail breaks"
tags: ["cs", "data-databases", "intermediate"]
domain: Data & Databases
level: intermediate
source: "https://en.wikipedia.org/wiki/Head/tail_breaks"
wikipedia_categories: ["Big data", "Data management", "Geographic information systems"]
related: ["[[Approximate inference]]", "[[Astroinformatics]]", "[[Big data]]", "[[Big memory]]", "[[Data exhaust]]", "[[Data lineage]]", "[[Data philanthropy]]", "[[Data stream management system]]", "[[Data version control]]", "[[Datafication]]"]
---

# Head/tail breaks

Head/tail breaks is a clustering algorithm for data with a heavy-tailed distribution such as power laws and lognormal distributions. The heavy-tailed distribution can be simply referred to the scaling pattern of far more small things than large ones, or alternatively numerous smallest, a very few largest, and some in between the smallest and largest. The classification is done through dividing things into large (or called the head) and small (or called the tail) things around the arithmetic mean or average, and then recursively going on for the division process for the large things or the head until the notion of far more small things than large ones is no longer valid, or with more or less similar things left only. Head/tail breaks is not just for classification, but also for visualization of big data by keeping the head, since the head is self-similar to the whole. Head/tail breaks can be applied not only to vector data such as points, lines and polygons, but also to raster data like digital elevation model (DEM).

## Related

- [[Approximate inference]]
- [[Astroinformatics]]
- [[Big data]]
- [[Big memory]]
- [[Data exhaust]]
- [[Data lineage]]
- [[Data philanthropy]]
- [[Data stream management system]]
- [[Data version control]]
- [[Datafication]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Head/tail_breaks