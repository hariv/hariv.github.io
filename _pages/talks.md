---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}
### GlucOS: Security, correctness, and simplicity for automated insulin delivery
MIT CSAIL Security Seminar 2024-2025, MIT Cambridge MA 02139 on Dec 12 2024<br/>
We present GlucOS, a novel system for trustworthy automated insulin delivery. Fundamentally, this
paper is about a system we designed, implemented, and deployed on real humans and the lessons
learned from our experiences. GlucOS combines algorithmic security, driver security, and end-to-end
verification to protect against malicious ML models, vulnerable pump drivers, and drastic changes in
human physiology. We use formal methods to prove correctness of critical components and incorporate
humans as part of our defensive strategy. Our evaluation includes both a real-world deployment with
seven individuals and results from simulation to show that our techniques generalize. Our results
show that GlucOS maintains safety and improves glucose control even under attack conditions. This
work demonstrates the potential for secure, personalized, automated healthcare systems.

### GlucOS: Security, correctness, and simplicity for automated insulin delivery
Computer Systems Seminar, UC Davis, Davis CA 95616on Oct 18 2024<br/>
Type 1 Diabetes (T1D) is a metabolic disorder where an individual’s pancreas stops producing
insulin. To compensate, they inject synthetic insulin. Computer systems, called automated insulin
delivery systems, exist that inject insulin automatically. However, insulin is a dangerous hormone,
where too much insulin can kill people in a matter of hours and too little insulin can kill people
in a matter of days. In this paper, we take on the challenge of building a new trustworthy
automated insulin delivery system, called GlucOS. In our design, we apply separation principles to
keep our implementation simple, we use formal methods to prove correct the most critical parts of
the system, and we design novel security mechanisms and policies to withstand malicious components
and attacks on the system. We report on real world use for one individual for 6 months using GlucOS.
Our data shows that for this individual, our MLbased algorithm runs safely and manages their T1D
effectively. We also run our system on 21 virtual humans using simulations and show that our
security and safety mechanisms enable ML to improve their core T1D measures of metabolic health by
4.3% on average. Finally, we show that our security and safety mechanisms maintain recommended
levels of control over T1D even in the face of active attacks that would have otherwise led to
death.

### Aragorn: A Privacy-Enhancing System for Mobile Cameras
UbiComp'24, Sofitel Melbourne on Collins, Melbourne VIC 3000 Australia on Oct 7 2024<br/>
Mobile app developers often rely on cameras to implement rich features. However, giving apps
unfettered access to the mobile camera poses a privacy threat when camera frames capture sensitive
information that is not needed for the app’s functionality. To mitigate this threat, we present
Aragorn, a novel privacy-enhancing mobile camera system that provides fine grained control over
what information can be present in camera frames before apps can access them. Aragorn automatically
sanitizes camera frames by detecting regions that are essential to an app’s functionality and
blocking out everything else to protect privacy while retaining app utility. Aragorn can cater to a
wide range of camera apps and incorporates knowledge distillation and crowdsourcing to extend robust
support to previously unsupported apps. In our evaluations, we see that, with no degradation in
utility, Aragorn detects credit cards with 89% accuracy and faces with 100% accuracy in context of
credit card scanning and face recognition respectively. We show that Aragorn’s implementation in the
Android camera subsystem only suffers an average drop of 0.01 frames per second in frame rate. Our
evaluations show that the overhead incurred by Aragorn to system performance is reasonable.

### GlucOS: Security, correctness, and simplicity for automated insulin delivery
FairComp Workshop @ UbiComp 2024, Sofitel Melbourne on Collins, Melbourne VIC 3000 Australia on Oct 5 2024<br/>
Type 1 Diabetes (T1D) is a metabolic disorder where an individual’s pancreas stops producing
insulin. To compensate, they inject synthetic insulin. Computer systems, called automated insulin
delivery systems, exist that inject insulin automatically. However, insulin is a dangerous hormone,
where too much insulin can kill people in a matter of hours and too little insulin can kill people
in a matter of days. In this paper, we take on the challenge of building a new trustworthy
automated insulin delivery system, called GlucOS. In our design, we apply separation principles to
keep our implementation simple, we use formal methods to prove correct the most critical parts of
the system, and we design novel security mechanisms and policies to withstand malicious components
and attacks on the system. We report on real world use for one individual for 6 months using GlucOS.
Our data shows that for this individual, our MLbased algorithm runs safely and manages their T1D
effectively. We also run our system on 21 virtual humans using simulations and show that our
security and safety mechanisms enable ML to improve their core T1D measures of metabolic health by
4.3% on average. Finally, we show that our security and safety mechanisms maintain recommended
levels of control over T1D even in the face of active attacks that would have otherwise led to
death.

### FP-Rowhammer: Rowhammer-Based Device Fingerprinting
UC Davis, Davis, CA 95616 on Feb 16 2024 <br/>
Device fingerprinting relies on attributes that capture heterogeneity in
hardware and software configurations to extract unique and stable fingerprints.
Fingerprinting countermeasures attempt to either present a uniform fingerprint
across different devices through normalization or present different fingerprints
for the same device each time through obfuscation. We present FP-Rowhammer, a
Rowhammer-based device fingerprinting approach that can build unique and stable
fingerprints even across devices with normalized or obfuscated hardware and
software configurations. To this end, FP-Rowhammer leverages the DRAM manufacturing
process variation that gives rise to unique distributions of Rowhammer-induced bit
flips across different DRAM modules.

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