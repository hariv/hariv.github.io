---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}
### FP-Rowhammer: Rowhammer-Based Device Fingerprinting
UC Davis, Davis, CA 95616 on Feb 16 2024
Device fingerprinting relies on attributes that capture heterogeneity in
hardware and software configurations to extract unique and stable fingerprints.
Fingerprinting countermeasures attempt to either present a uniform fingerprint
across different devices through normalization or present different fingerprints
for the same device each time through obfuscation. We present FP-Rowhammer, a
Rowhammer-based device fingerprinting approach that can build unique and stable
fingerprints even across devices with normalized or obfuscated hardware and
software configurations. To this end, FP-Rowhammer leverages the DRAM manufacturing
process variation that gives rise to unique distributions of Rowhammer-induced bit
flips across different DRAM modules. Our evaluation on a test bed of 98 DRAM modules
shows that FP-Rowhammer achieves 99.91\% fingerprinting accuracy. FP-Rowhammer's
fingerprints are also stable, with no degradation in fingerprinting accuracy over
a period of ten days.FP-Rowhammer is the first Rowhammer fingerprinting approach
that is able to extract unique and stable fingerprints efficiently and at scale.

### Aragorn: An Automated and Extensible Privacy-Enhancing System for Mobile Cameras
UC Davis, Davis, CA 95616 on Jan 21 2022  
Mobile app developers often rely on high-quality
cameras to implement rich functionalities. However, giving apps
unfettered access to the mobile camera poses a serious threat
to user privacy because camera frames may contain sensitive
information that is beyond the scope of the app. To mitigate this
privacy concern, we present Aragorn, a novel privacy-enhancing
mobile camera system that automatically sanitizes camera frames
to only contain user-authorized objects without needing any
manual user input.

### eXeGAN: Not all Malware is created Equal
Blue Hexagon, Sunnyvale, CA 94086 on Sep 20 2019    
Antivirus engines use static analysis of executables to detect malware. In some cases,
they prefer static analysis over dynamic analysis since dynamic analysis is time
consuming and can be unreliable if the malware detects that it is being executed in a
sandboxed environment for analysis. The advent of machine learning has greatly shifted
malware detection in favor of these engines, since ML models tend to generalize,
helping them detect completely new and unseen types of malware. We explore if malware
authors can also leverage machine learning to evade detection by presenting eXeGAN, a
generative adversarial network that mutates executables to evade ML and ruled based
static detection, while preserving their functionality.