---
title: "Time-utility function"
tags: ["cs", "general-cs", "intermediate"]
domain: General CS
level: intermediate
source: "https://en.wikipedia.org/wiki/Time-utility_function"
wikipedia_categories: ["Optimal scheduling", "Quality of service", "Real-time computing", "Software performance management"]
related: ["[[Earliest deadline first scheduling]]", "[[YDS algorithm]]", "[[ALTQ]]", "[[AQuoSA]]", "[[Arthur Pollen]]", "[[CompactDAQ]]", "[[CompactRIO]]", "[[CPU shielding]]", "[[Differentiated services]]", "[[Earliest eligible virtual deadline first scheduling]]"]
---

# Time-utility function

A Time/Utility Function (TUF), née Time/Value Function, specifies the application-specific utility that an action (e.g., computational task, mechanical movement) yields depending on its completion time. TUFs and their utility interpretations (semantics), scales, and values are derived from application domain-specific subject matter knowledge. An example (but not the only) interpretation of utility is an action's relative importance, which otherwise is independent of its timeliness. The traditional deadline represented as a TUF is a special case—a downward step of utility from 1 to 0 at the deadline time—e.g., timeliness without importance. A TUF is more general—it has a critical time, with application-specific shapes and utility values on each side, after which it does not increase. The various researcher and practitioner definitions of firm and soft real-time can also be represented as special cases of the TUF model. 
The optimality criterion for scheduling multiple TUF-constrained actions has historically in the literature been only maximal utility accrual (UA)—e.g., a (perhaps expected) weighted sum of the individual actions' completion utilities. This thus takes into account timeliness with respect to critical times. Additional criteria (e.g., energy, predictability), constraints (e.g., dependencies), system models, scheduling algorithms, and assurances have been added as the TUF/UA paradigm and its use cases have evolved. More expressively, TUF/UA allows accrued utility, timeliness, predictability, and other scheduling criteria and constraints to be traded off against one another for the schedule to yield situational application QoS—as opposed to only timeliness per se. Instances of the TUF/UA paradigm have been employed in a wide variety of application domains, most frequently in military systems.

## Related

- [[Earliest deadline first scheduling]]
- [[YDS algorithm]]
- [[ALTQ]]
- [[AQuoSA]]
- [[Arthur Pollen]]
- [[CompactDAQ]]
- [[CompactRIO]]
- [[CPU shielding]]
- [[Differentiated services]]
- [[Earliest eligible virtual deadline first scheduling]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Time-utility_function