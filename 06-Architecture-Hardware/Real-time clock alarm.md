---
title: "Real-time clock alarm"
tags: ["cs", "architecture-hardware", "intermediate"]
domain: Architecture & Hardware
level: intermediate
source: "https://en.wikipedia.org/wiki/Real-time_clock_alarm"
wikipedia_categories: ["Alarms", "BIOS", "Operating system technology", "Real-time clocks", "Unified Extensible Firmware Interface"]
related: ["[[PXE boot]]", "[[System time]]", "[[ALTQ]]", "[[Application binary interface]]", "[[Apptainer]]", "[[Asynchronous system trap]]", "[[Attached Support Processor]]", "[[Binary Application Markup Language]]", "[[Boot sector]]", "[[Busdma]]"]
---

# Real-time clock alarm

A real time clock alarm is a feature that can be used to allow a computer to 'wake up' after shutting down to execute tasks every day or on a certain day. It can sometimes be found in the power management section of a motherboard's BIOS/UEFI setup. Wake On LAN, Wake on ring, and IPMI functions could also be used to start a computer after it is turned off.
In Linux, the real time clock alarm can be set or retrieved using /proc/acpi/alarm or /sys/class/rtc/rtc0/wakealarm. Alternatively, the rtcwake utility may be used which prevents problems when using local time instead of UTC by automatically processing the /etc/adjtime file. systemd can be used to wake a system and run a task at a specific time.
In Microsoft Windows there are different programs which could be used to 'wake up' a computer from standby or hibernation. Task Scheduler settings for power management can be used to 'Wake the computer to run this task'.

## Related

- [[PXE boot]]
- [[System time]]
- [[ALTQ]]
- [[Application binary interface]]
- [[Apptainer]]
- [[Asynchronous system trap]]
- [[Attached Support Processor]]
- [[Binary Application Markup Language]]
- [[Boot sector]]
- [[Busdma]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Real-time_clock_alarm