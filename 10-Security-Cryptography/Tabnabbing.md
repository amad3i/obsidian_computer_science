---
title: "Tabnabbing"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Tabnabbing"
wikipedia_categories: ["Cybercrime", "Firefox", "Social engineering (security)"]
related: ["[[CovidLock]]", "[[Cyber espionage]]", "[[Cyber espionage on universities]]", "[[Cyberwarfare]]", "[[Darcula]]", "[[Domain name scams]]", "[[Email spoofing]]", "[[Emergency data request]]", "[[FraudWatch International]]", "[[Infostealer]]"]
---

# Tabnabbing

Tabnabbing is a computer exploit and phishing attack, which persuades users to submit their login details and passwords to popular websites by impersonating those sites and convincing the user that the site is genuine. The attack's name was coined in early 2010 by Aza Raskin, a security researcher and design expert. The attack takes advantage of user trust and inattention to detail in regard to tabs, and the ability of browsers to navigate across a page's origin in inactive tabs a long time after the page is loaded. Tabnabbing is different from most phishing attacks in that the user no longer remembers that a certain tab was the result of a link unrelated to the login page, because the fake login page is loaded in one of the long-lived open tabs in their browser.
The attack causes the browser to navigate to the impersonated page after the page has been left unattended for some time. A user who returns after a while and sees the login page may be induced to believe the page is legitimate and enter their login, password and other details that will be used for improper purposes. The attack can be made more likely to succeed if the attacker is able to check for well known websites the user has loaded in the past or in other tabs, and loads a simulation of the same sites. This attack can be done even if JavaScript is disabled, using the "meta refresh" meta element, an HTML attribute used for page redirection that causes a reload of a specified new page after a given time interval.
The NoScript extension for Mozilla Firefox defends both from the JavaScript-based and from the scriptless attack, based on meta refresh, by preventing inactive tabs from changing the location of the page. Because there are legitimate purposes for inactive tab redirects, it cannot be disabled in all browsers by default without breaking some applications. The attack is also not very common, giving browser vendors little incentive to implement a breaking change.

## Related

- [[CovidLock]]
- [[Cyber espionage]]
- [[Cyber espionage on universities]]
- [[Cyberwarfare]]
- [[Darcula]]
- [[Domain name scams]]
- [[Email spoofing]]
- [[Emergency data request]]
- [[FraudWatch International]]
- [[Infostealer]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Tabnabbing