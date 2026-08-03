---
title: "Modifiable areal unit problem"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Modifiable_areal_unit_problem"
wikipedia_categories: ["Bias", "Geographic information systems", "Problems in spatial analysis"]
related: ["[[Neighborhood effect averaging problem]]", "[[Uncertain geographic context problem]]", "[[Modifiable temporal unit problem]]", "[[3D structure change detection]]", "[[Address geocoding]]", "[[Algorithmic bias]]", "[[AM-FM-GIS]]", "[[Android Team Awareness Kit]]", "[[Automatic label placement]]", "[[Book of Roads and Kingdoms]]"]
---

# Modifiable areal unit problem

The modifiable areal unit problem (MAUP) is a source of statistical bias that can significantly impact the results of statistical hypothesis tests. The MAUP affects results when point-based measures of spatial phenomena are aggregated into spatial partitions or areal units (such as regions or districts) as in, for example, population density or illness rates. The resulting summary values (e.g., totals, rates, proportions, densities) are influenced by both the shape and scale of the aggregation unit.
For example, census data may be aggregated into county districts, census tracts, postcode areas, police precincts, or any other arbitrary spatial partition. Thus, the results of data aggregation are dependent on the mapmaker's choice of which "modifiable areal unit" to use in their analysis. A census choropleth map calculating population density using state boundaries will yield radically different results from a map that calculates density based on county boundaries. Furthermore, census district boundaries are also subject to change over time, meaning the MAUP must be considered when comparing past to current data.

## Related

- [[Neighborhood effect averaging problem]]
- [[Uncertain geographic context problem]]
- [[Modifiable temporal unit problem]]
- [[3D structure change detection]]
- [[Address geocoding]]
- [[Algorithmic bias]]
- [[AM-FM-GIS]]
- [[Android Team Awareness Kit]]
- [[Automatic label placement]]
- [[Book of Roads and Kingdoms]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Modifiable_areal_unit_problem