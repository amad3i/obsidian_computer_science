---
title: "Thermal attack"
tags: ["cs", "security-cryptography", "intermediate"]
domain: Security & Cryptography
level: intermediate
source: "https://en.wikipedia.org/wiki/Thermal_attack"
wikipedia_categories: ["Computer security"]
related: ["[[2018 Google data breach]]", "[[2024 National Public Data breach]]", "[[Adrozek]]", "[[Adversarial machine learning]]", "[[Anderson's rule (computer science)]]", "[[Anomaly Detection at Multiple Scales]]", "[[Anthem medical data breach]]", "[[Attack path management]]", "[[Automated penetration testing]]", "[[Automotive security]]"]
---

# Thermal attack

A thermal attack (aka thermal imaging attack) is an approach that exploits heat traces to uncover the entered credentials. These attacks rely on the phenomenon of heat transfer from one object to another. During authentication, heat transfers from the users' hands to the surface they are interacting with, leaving heat traces behind that can be analyzed using thermal cameras that operate in the far-infrared spectrum. These traces can be recovered and used to reconstruct the passwords. In some cases, the attack can be successful even 30 seconds after the user has authenticated.
Thermal attacks can be performed after the victim had authenticated, alleviating the need for in-situ observation attacks (e.g., shoulder surfing attacks) that can be affected by hand occlusions. While smudge attacks can reveal the order of entries of graphical passwords, such as the Android Lock Patterns, thermal attacks can reveal the order of entries even in the case of PINs or alphanumeric passwords. The reason thermal attacks leak information about the order of entry is because keys and buttons that the user touches first lose heat over time, while recently touched ones maintain the heat signature for a longer time. This results in distinguishable heat patterns that can tell the attacker which entry was entered first.
Thermal attacks were shown to be effective against plastic keypads, such as the ones used to enter credit card's PINs in supermarkets and restaurants, and on handheld mobile devices such as smartphones and tablets.
In their paper published at the Conference on Human Factors in Computing Systems (CHI 2017), Abdelrahman et al. showed that the attack is feasible on today's smartphones. They also proposed some ways to mitigate the attack, such as swiping randomly on the screen to distort the heat traces, or forcing maximum CPU usage for a few seconds.
Thermal attacks can also infer passwords from heat traces on keyboards. Researchers at the University of Glasgow showed that attackers who use AI methods can be more effective in performing thermal attacks. Their study presents a new tool called ThermoSecure and evaluates it in two user studies. The results show that ThermoSecure can successfully attack passwords with an average accuracy of 92% to 55%, depending on the length of the password. The effectiveness of thermal attacks also depends on typing behavior and the material of the keycaps. ABS keycaps, which retain heat traces longer, are more vulnerable to thermal attacks. The study also discusses ways to protect against thermal attacks and presents seven potential mitigation approaches. 
Dr Khamis, who led the development of the technology with Norah Alotaibi and John Williamson, said with thermal imaging cameras more affordable than ever and machine learning becoming more accessible, it was "very likely that people around the world are developing systems along similar lines to ThermoSecure in order to steal passwords".

## Related

- [[2018 Google data breach]]
- [[2024 National Public Data breach]]
- [[Adrozek]]
- [[Adversarial machine learning]]
- [[Anderson's rule (computer science)]]
- [[Anomaly Detection at Multiple Scales]]
- [[Anthem medical data breach]]
- [[Attack path management]]
- [[Automated penetration testing]]
- [[Automotive security]]

## Sources

- Wikipedia: https://en.wikipedia.org/wiki/Thermal_attack