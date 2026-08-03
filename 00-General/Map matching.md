---
title: "Map matching"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Map_matching"
wikipedia_categories: ["Computing terminology", "Geographic information systems"]
related: ["[[3D structure change detection]]", "[[Address geocoding]]", "[[Address space]]", "[[AM-FM-GIS]]", "[[Android Team Awareness Kit]]", "[[Application posture]]", "[[Automatic label placement]]", "[[Blocking (computing)]]", "[[Book of Roads and Kingdoms]]", "[[Buffer analysis]]"]
---

# Map matching

Map matching is the problem of how to match recorded geographic coordinates to a logical model of the real world, typically using some form of Geographic Information System. The most common approach is to take recorded, serial location points (e.g. from GPS) and relate them to edges in an existing street graph (network), usually in a sorted list representing the travel of a user or vehicle. Matching observations to a logical model in this way has applications in satellites navigation, GPS tracking of freight, and transportation engineering.
Map matching algorithms can be divided in real-time and offline algorithms. Real-time algorithms associate the position during the recording process to the road network. Offline algorithms are used after the data is recorded and are then matched to the road network. Real-time applications can only calculate based upon the points prior to a given time (as opposed to those of a whole journey), but are intended to be used in 'live' environments. This brings a compromise of performance over accuracy. Offline applications can consider all points and so can tolerate slower performance in favour of accuracy. However, the defects on low accuracy can be reduced due to integration of spatio-temporal proximity and improved weighted circle algorithms.

## Related

- [[3D structure change detection]]
- [[Address geocoding]]
- [[Address space]]
- [[AM-FM-GIS]]
- [[Android Team Awareness Kit]]
- [[Application posture]]
- [[Automatic label placement]]
- [[Blocking (computing)]]
- [[Book of Roads and Kingdoms]]
- [[Buffer analysis]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Map_matching