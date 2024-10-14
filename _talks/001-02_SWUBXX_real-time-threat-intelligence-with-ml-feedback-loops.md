---
accepted: true
code: SWUBXX
details: true
keynote: false
layout: talk
speakers:
- bio: Tomer is a security research team lead in Cato Research Labs at Cato Networks,
    with a keen interest in various aspects of cybersecurity, including reverse engineering,
    network protocol analysis, and detecting malicious traffic. Additionally, Tomer
    is enthusiastic about machine learning and thrives on tackling intricate challenges
    within this field. Presently, his main area of focus is network-based security
    research, where he endeavors to devise innovative approaches for detecting threats
    in corporate network settings.
  handle: false
  name: Tomer Doitshman
  photo: https://pretalx.com/media/avatars/TWD3EG_gYv2gfp.jpeg
timeslot:
  duration: 30
  end: 2024-11-11 10:30:00+01:00
  start: 2024-11-11 10:00:00+01:00
title: Real-Time Threat Intelligence with ML Feedback Loops
track: 1
---

Threat intelligence is one of the most critical lines of defense today for safeguarding organizations from malware and other potential attack vectors that can compromise business continuity and stability.
This talk will delve into the design and implementation of a sophisticated threat intelligence feedback loop, leveraging machine learning to classify and manage millions of potential Indicators of Compromise (IOCs), aggregating and analyzing huge amounts of data in near real time.

This system built upon a robust cloud native & OSS stack powered by Kubernetes and Prometheus continuously scans the internet, social media, and various blogs, employing sentiment analysis to gauge the potential maliciousness of IOCs, which include domains, IP addresses, user agents, browser extensions, URIs, URLs, IP ranges, and more.
A classification tree model then assigns a "maliciousness" score to each IOC.

Malicious IOCs identified by the model are aggregated into a list and deployed into the production environment to block network communications involving these IOCs.
The production environment generates feedback on the effectiveness of these blocks, summarizing user complaints and the frequency of block occurrences to assess the validity of the IOCs.
The unique nature of this feedback is its ability to be looped back into the machine learning model rapidly from the users and network hosts, enabling near real time updates and refinement of the IOC classification scores.
The model re-evaluates the IOCs to determine their legitimacy, significantly minimizing false positives, enabling the detection of novel threats as they evolve and happen,  enhancing overall accuracy of the threat intelligence model.
This continuous feedback loop allows the model to improve over time and ensures that the system adapts dynamically to emerging threats, maintaining robust organizational security.

Join us to unpack how this feedback loop was built and works under the hood, its impact on threat intelligence and its continuous evolution, and the advancements in machine learning that drive advancements across the security domain.