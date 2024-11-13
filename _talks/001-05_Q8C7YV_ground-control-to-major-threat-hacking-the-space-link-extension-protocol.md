---
accepted: true
code: Q8C7YV
details: true
keynote: false
layout: talk
speakers:
- bio: "Offensive Security Engineer with over 15 years in the space industry, working
    as a Software Engineer and Technical Project Manager. For the past few years,
    he has focused on offensive security, specializing in vulnerability research,
    exploit development. Holds a number of OffSec certifications, and has been credited
    with several CVEs.\r\n\r\nhttps://x.com/0x4ndy\r\nhttps://linkedin.com/in/andrzejolchawa"
  handle: false
  name: Andrzej Olchawa
  photo: https://pretalx.com/media/avatars/SDYTSV_BScA7P2.jpeg
timeslot:
  duration: 30
  end: 2024-11-11 12:30:00+01:00
  start: 2024-11-11 12:00:00+01:00
title: Ground Control to Major Threat - Hacking the Space Link Extension Protocol
track: 1
recording_uri: http://youtu.be/CJncXmQ5RYw
slides_uri:
---

Space missions have increasingly been the subject in the context of security breaches and satellite hacks.
The majority of discussions revolve around direct communication and access to spacecraft through means such as Software Defined Radio.
However, the reality is that this approach isn't practical for most adversaries, as it requires substantial resources and is easily detectable due to the power and radio frequencies required to command a spacecraft.
Instead, adversaries might shift their focus away from the Space Segment and opt for a more practical approach, such as accessing and exploiting the Ground Segment vulnerabilities and flaws in order to gain control over spacecraft.
Every space mission comprises custom-made hardware and software components, which interact with each other utilizing dedicated protocols and standards designed and developed for this sole purpose.
Numerous potential failure points can adversely impact a space mission, many of which persist on the ground.
Considering the essential services they facilitate and the extent to which contemporary society relies on space technology, each component utilized in space missions should be regarded as integral to critical infrastructure and treated as such, particularly from a security standpoint.
This study centers on the Space Link Extension (SLE) protocol, which is employed as a standard for communication between mission data systems and ground stations by various space agencies and organizations, including NASA and ESA.
We will address the security concerns inherent in the SLE protocol.
At the same time, we demonstrate methods and techniques malicious actors can employ to conduct a Denial of Service (DoS) or tap into the ground station communications, gaining control over an actual spacecraft.
We will conclude this publication by presenting the reader with a possible mitigation strategy that we believe should be employed at the SLE protocol level.
Additionally, we will outline a forecast for future work, detailing both planned endeavors and those already in progress, to further expand on this research.