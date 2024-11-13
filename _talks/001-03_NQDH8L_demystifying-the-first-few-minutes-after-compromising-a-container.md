---
accepted: true
code: NQDH8L
details: true
keynote: false
layout: talk
speakers:
- bio: Stuart is a Lead Engineer on the Offensive Security team at Klarna, where he
    focuses on Red Teaming, Unix, and general Swiss Army knifery. He's been on the
    offensive side of public and private sector security for upwards of a decade,
    during which time he's been an operator and trainer and developed a small arsenal
    of public and private offensive tools.
  handle: false
  name: Stuart McMurray
  photo: https://pretalx.com/media/avatars/SUCUBB_KbPmGvG.png
timeslot:
  duration: 30
  end: 2024-11-11 11:00:00+01:00
  start: 2024-11-11 10:30:00+01:00
title: Demystifying the First Few Minutes After Compromising a Container
track: 1
recording_uri: 
slides_uri: /files/slides/001-03_NQDH8L_demystifying-the-first-few-minutes-after-compromising-a-container.pdf
---

Meant for a less-offensive but still technical audience, this talk presents a hands-on look at Linux container post-compromise.
 It will cover why a hacker compromises a container and what he hopes to get out of it, C2 comms from the container back to the attacker, information extraction, and breaking out and then into other containers.

Throughout, the concept of what a container is will be a recurring theme, starting as a config which runs an application and then refined as the talk progresses to Linux processes which share common namespaces.

The talk is aimed at giving blue teams, systems administrators, and devops engineers a clearer picture of how an attacker could interact with what they create and defend with the ultimate goal of better-informed defensive and architectural choices.
 Pentesters and red teamers should also find it helpful.

It is not a checklist of configuration settings or a magic SIEM/SOAR/such query but rather a different point of view.
 There will be no 0days or kernel tomfoolery of the cc exploit && ./exploit variety but rather good old-fashioned Linux sneakiness and shell gymnastics in the modern age.