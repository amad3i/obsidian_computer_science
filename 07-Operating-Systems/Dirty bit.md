---
title: "Dirty bit"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/Dirty_bit"
wikipedia_categories: ["Central processing unit", "Operating system technology"]
related: ["[[Control register]]", "[[Flag (programming)]]", "[[Protection ring]]", "[[ALTQ]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Arithmetic logic unit]]", "[[Asynchronous system trap]]", "[[Attached Support Processor]]", "[[Binary Application Markup Language]]"]
---

# Dirty bit

A dirty bit or modified bit is a bit that is associated with a block of computer memory and indicates whether the corresponding block of memory has been modified. The dirty bit is set when the processor writes to (modifies) this memory. The bit indicates that its associated block of memory has been modified and has not been saved to  storage  yet. When a block of memory is to be replaced, its corresponding dirty bit is checked to see if the block needs to be written back to secondary memory before being replaced or if it can simply be removed. Dirty bits are used by the CPU cache and in the page replacement algorithms of an operating system.
Dirty bits can also be used in incremental computing by marking segments of data that need to be processed or have yet to be processed. This technique can be used with delayed computing to avoid unnecessary processing of objects or states that have not changed. When the model is updated (usually by multiple sources), only the segments that need to be reprocessed will be marked dirty. Afterwards, an algorithm will scan the model for dirty segments and process them, marking them as clean. This ensures the unchanged segments are not recalculated and saves processor time.

## Related

- [[Control register]]
- [[Flag (programming)]]
- [[Protection ring]]
- [[ALTQ]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Arithmetic logic unit]]
- [[Asynchronous system trap]]
- [[Attached Support Processor]]
- [[Binary Application Markup Language]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Dirty_bit