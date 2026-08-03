---
title: "DeviceKit"
tags: ["cs", "software-engineering", "intermediate"]
domain: Software Engineering
level: intermediate
source: "https://en.wikipedia.org/wiki/DeviceKit"
wikipedia_categories: ["Applications using D-Bus", "Free and open-source software stubs", "Free system software", "Freedesktop.org", "Human–computer interaction", "Software using the GNU General Public License", "User interfaces"]
related: ["[[HAL (software)]]", "[[ASCEND]]", "[[CheetahTemplate]]", "[[CSS framework]]", "[[ELMER guidelines]]", "[[ESP-r]]", "[[Interaction technique]]", "[[Linux kernel]]", "[[Mode (user interface)]]", "[[Organic user interface]]"]
---

# DeviceKit

DeviceKit is a modular hardware abstraction layer designed for use in Linux systems that is designed to simplify device management and replace the current monolithic Linux HAL. DeviceKit includes the ability to enumerate system devices and send notifications when hardware is added or removed from the computer system.
In May 2008, HAL developer David Zeuthen announced his intention to deprecate HAL, mainly because of its complexity and redundancy with other libraries in the Linux environment. The only missing part in those libraries would be a centralized service to enumerate existing devices, signal adding/removal of devices and merging and classifying available hardware information in one point. DeviceKit is the new library providing those services, while the hardware is supposed to be accessed through other libraries instead of HAL or DeviceKit.
The first distribution to include DeviceKit was Fedora 11. Ubuntu 9.10 replaced some of the old HAL features with DeviceKit and functionality from udev.
On 1 December 2009, it was announced that DeviceKit-disks was renamed to udisks and that a similar rename would happen for DeviceKit-power.

## Related

- [[HAL (software)]]
- [[ASCEND]]
- [[CheetahTemplate]]
- [[CSS framework]]
- [[ELMER guidelines]]
- [[ESP-r]]
- [[Interaction technique]]
- [[Linux kernel]]
- [[Mode (user interface)]]
- [[Organic user interface]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/DeviceKit