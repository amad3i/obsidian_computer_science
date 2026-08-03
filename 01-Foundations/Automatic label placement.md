---
title: "Automatic label placement"
tags: ["cs", "foundations-math", "intermediate"]
domain: Foundations & Math
level: intermediate
source: "https://en.wikipedia.org/wiki/Automatic_label_placement"
wikipedia_categories: ["Geographic information systems", "Optimization algorithms and methods"]
related: ["[[3D structure change detection]]", "[[Address geocoding]]", "[[Alpha–beta pruning]]", "[[AM-FM-GIS]]", "[[Android Team Awareness Kit]]", "[[Ant colony optimization algorithms]]", "[[Backtracking line search]]", "[[Barzilai–Borwein method]]", "[[Best arm identification]]", "[[Book of Roads and Kingdoms]]"]
---

# Automatic label placement

Automatic label placement, sometimes called text placement or name placement, comprises the computer methods of placing labels automatically on a map or chart. This is related to the typographic design of such labels.
The typical features depicted on a geographic map are line features (e.g. roads), area features (countries, parcels, forests, lakes, etc.), and point features (villages, cities, etc.). In addition to depicting the map's features in a geographically accurate manner, it is of critical importance to place the names that identify these features, in a way that the reader knows instantly which name describes which feature.
Automatic text placement is one of the most difficult, complex, and time-consuming problems in mapmaking and GIS (Geographic Information System). Other kinds of computer-generated graphics – like charts, graphs etc. – require good placement of labels as well, not to mention engineering drawings, and professional programs which produce these drawings and charts, like spreadsheets (e.g. Microsoft Excel) or computational software programs (e.g. Mathematica).
Naively placed labels overlap excessively, resulting in a map that is difficult or even impossible to read. Therefore, a GIS must allow a few possible placements of each label, and often also an option of resizing, rotating, or even removing (suppressing) the label. Then, it selects a set of placements that results in the least overlap, and has other desirable properties. For all but the most trivial setups, the problem is NP-hard.

## Related

- [[3D structure change detection]]
- [[Address geocoding]]
- [[Alpha–beta pruning]]
- [[AM-FM-GIS]]
- [[Android Team Awareness Kit]]
- [[Ant colony optimization algorithms]]
- [[Backtracking line search]]
- [[Barzilai–Borwein method]]
- [[Best arm identification]]
- [[Book of Roads and Kingdoms]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Automatic_label_placement