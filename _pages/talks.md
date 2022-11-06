---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

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
Antivirus engines use static analysis of executables to detect malware. In some cases, they prefer
static analysis over dynamic analysis since dynamic analysis is time consuming and can be unreliable
if the malware detects that it is being executed in a sandboxed environment for analysis. The advent of
machine learning has greatly shifted malware detection in favor of these engines, since ML models tend
to generalize, helping them detect completely new and unseen types of malware. We explore if malware
authors can also leverage machine learning to evade detection by presenting eXeGAN, a generative adversarial
network that mutates executables to evade ML and ruled based static detection, while preserving their
functionality.