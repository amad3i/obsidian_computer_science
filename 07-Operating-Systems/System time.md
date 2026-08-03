---
title: "System time"
tags: ["cs", "operating-systems", "intermediate"]
domain: Operating Systems
level: intermediate
source: "https://en.wikipedia.org/wiki/System_time"
wikipedia_categories: ["Computer programming", "Operating system technology", "Real-time clocks"]
related: ["[[Real-time clock alarm]]", "[[Algorave]]", "[[ALTQ]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Asynchronous procedure call]]", "[[Asynchronous system trap]]", "[[Asynchrony (computer programming)]]", "[[Attached Support Processor]]", "[[Bayesian program synthesis]]"]
---

# System time

In computing, system time represents a computer system's notion of a point in time.
System time is measured by a system clock, which is typically implemented as a simple count of the number of ticks that have transpired since some arbitrary starting date, called the epoch. For example, Unix and POSIX-compliant systems encode system time ("Unix time") as the number of seconds elapsed since the start of the Unix epoch at 1 January 1970 00:00:00 UT, with exceptions for leap seconds. Systems that implement the 32-bit and 64-bit versions of the Windows API, such as Windows 9x and Windows NT, provide the system time as both SYSTEMTIME, represented as a year/month/day/hour/minute/second/milliseconds value, and FILETIME, represented as a count of the number of 100-nanosecond ticks since 1 January 1601 00:00:00 UT as reckoned in the proleptic Gregorian calendar.
System time can be converted into calendar time, which is a form more suitable for human comprehension. For example, the Unix system time 1000000000 seconds since the beginning of the epoch translates into the calendar time 9 September 2001 01:46:40 UT. Library subroutines that handle such conversions may also deal with adjustments for time zones, daylight saving time (DST), leap seconds, and the user's locale settings. Library routines are also generally provided that convert calendar times into system times.
Many implementations that currently store system times as 32-bit integer values will suffer from problems such as the impending Year 2038 problem. These time values will overflow ("run out of bits") after the end of their system time epoch, leading to software and hardware errors. These systems will require some form of remediation, similar to efforts required to solve the earlier Year 2000 problem. This will also be a potentially much larger problem for existing data file formats that contain system timestamps stored as 32-bit values.

## Related

- [[Real-time clock alarm]]
- [[Algorave]]
- [[ALTQ]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Asynchronous procedure call]]
- [[Asynchronous system trap]]
- [[Asynchrony (computer programming)]]
- [[Attached Support Processor]]
- [[Bayesian program synthesis]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/System_time