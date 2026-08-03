---
title: "Simple Features"
tags: ["cs", "ai-machine-learning", "intermediate"]
domain: AI & Machine Learning
level: intermediate
source: "https://en.wikipedia.org/wiki/Simple_Features"
wikipedia_categories: ["Geographic information systems", "ISO/TC 211", "Open Geospatial Consortium", "Spatial database management systems"]
related: ["[[Spatial reference system]]", "[[Observations and Measurements]]", "[[OGC Reference Model]]", "[[Sensor Observation Service]]", "[[SensorThings API]]", "[[3D structure change detection]]", "[[Address geocoding]]", "[[AM-FM-GIS]]", "[[Android Team Awareness Kit]]", "[[Automatic label placement]]"]
---

# Simple Features

Simple Features (officially Simple Feature Access) is a set of standards that specify a common storage and access model of geographic features made of mostly two-dimensional geometries (point, line, polygon, multi-point, multi-line, etc.) used by geographic databases and geographic information systems.
It is formalized by both the Open Geospatial Consortium (OGC) and  the International Organization for Standardization (ISO).
The ISO 19125 standard comes in two parts. Part 1, ISO 19125-1 (SFA-CA for "common architecture"), defines a model for two-dimensional simple features, with linear interpolation between vertices, defined in a hierarchy of classes; this part also defines representation of geometry in text and binary forms. Part 2 of the standard, ISO 19125-2 (SFA-SQL), defines a "SQL/MM" language binding API for SQL under the prefix "ST_". The open access OGC standards cover additionally APIs for CORBA and OLE/COM, although these have lagged behind the SQL one and are not standardized by ISO. There are also adaptations to other languages covered below.
The ISO/IEC 13249-3 SQL/MM Spatial extends the Simple Features data model, originally based on straight-line segments, adding circular interpolations (e.g. circular arcs) and other features like coordinate transformations and methods for validating geometries, as well as Geography Markup Language support.

## Related

- [[Spatial reference system]]
- [[Observations and Measurements]]
- [[OGC Reference Model]]
- [[Sensor Observation Service]]
- [[SensorThings API]]
- [[3D structure change detection]]
- [[Address geocoding]]
- [[AM-FM-GIS]]
- [[Android Team Awareness Kit]]
- [[Automatic label placement]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Simple_Features