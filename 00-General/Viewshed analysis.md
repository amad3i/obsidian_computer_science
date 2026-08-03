---
title: "Viewshed analysis"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Viewshed_analysis"
wikipedia_categories: ["Communication design", "Geographic information systems"]
related: ["[[Cartographic generalization]]", "[[3D structure change detection]]", "[[Address geocoding]]", "[[AM-FM-GIS]]", "[[Android Team Awareness Kit]]", "[[Automatic label placement]]", "[[Book of Roads and Kingdoms]]", "[[Buffer analysis]]", "[[Canada Geographic Information System]]", "[[Change detection (GIS)]]"]
---

# Viewshed analysis

Viewshed analysis is a computational algorithm that delineates a viewshed, the area that is visible (on the base terrain surface) from a given location. It is a common part of the terrain analysis toolset found in most geographic information system (GIS) software. The analysis uses the elevation value of each cell of the digital elevation model (DEM) to determine visibility to or from a particular cell. The location of this particular cell varies depending on the needs of the analysis. 
For example, a viewshed analysis is commonly used to locate communication towers or determining the view from a road. Viewsheds can be calculated using an individual point such as a tower or multiple points such as a line representing a road. When analyzing a line segment, each of the vertices along the line is calculated to determine its visible area. The process can also be reversed. For example, when locating a landfill, the analysis can determine from where the landfill is visible to keep it hidden from view.

## Related

- [[Cartographic generalization]]
- [[3D structure change detection]]
- [[Address geocoding]]
- [[AM-FM-GIS]]
- [[Android Team Awareness Kit]]
- [[Automatic label placement]]
- [[Book of Roads and Kingdoms]]
- [[Buffer analysis]]
- [[Canada Geographic Information System]]
- [[Change detection (GIS)]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Viewshed_analysis