---
accepted: true
code: SV3TUN
details: true
keynote: false
layout: talk
speakers:
- bio: "Daniel Feichter is 38 years old, from Austria, and goes by the pseudonym VirtualAllocEx
    on Twitter and elsewhere. He originally comes from a background in electronics
    and communications engineering, and started as a junior penetration tester in
    2018. He found his purpose in ethical hacking and can't imagine doing anything
    else since. At the end of 2021, he decided to start his own company called RedOps
    to live out his research spirit and focus even more on his main area of interest.\r\n\r\nHis
    focus is on continuing to learn about Windows Internals, endpoint security, malware
    development, and reverse engineering. He regularly shares his research in the
    form of blog posts, conference talks, and workshops. He has spoken and taught
    at conferences such as DEFCON 30 (Adversary Village), DEFCON 31 (Red Team Village),
    SANS Hackfest, BSides Munich, MCTTP, etc. \r\n\r\nSince October 2024, Daniel has
    joined the ARES Red Team at NVISO and works there as a Red Team Operator.\r\n\r\nWhen
    not in front of the computer, he enjoys spending time with his family and friends,
    playing tennis, and has been practicing taekwondo regularly for over ten years."
  handle: false
  name: Daniel Feichter
  photo: https://pretalx.com/media/avatars/C3GT7F_tVTndoz.jpg
timeslot:
  duration: 30
  end: 2024-11-11 12:00:00+01:00
  start: 2024-11-11 11:30:00+01:00
title: 'EDR Analysis: An Introduction to Reversing Sophisticated Detection'
track: 1
---

Today, a prep phase against endpoint protection (EPP) and endpoint detection and response (EDR) products is part of every red team engagement, and preparing to create evasive malware that bypasses the targeted EDR to gain initial access can often be very time consuming.
In general, when preparing malware such as a shellcode loader or similar, we want to be as sure as possible that our malware will be able to bypass the targeted EDR.
The simplest approach is to start building malware and use trial and error to see if your malware is able to evade the EDR (evasion defined as not prevented and not detected) or if the malware is caught by the EDR.
In order to build not only better, but more effective malware, it really helps to go beyond trial and error testing and start investing time and energy in reversing and debugging EDRs and trying to better understand the logic of the detection mechanisms they implement.

To build more evasive or effective malware, you need to know your enemy, in this case the EDR.
By now most community members are aware that modern EDRs use things like the Antimalware Scan Interface (AMSI) to detect malicious powershell activity, or use user mode hooking to detect potentially malicious behaviour in the context of Windows APIs, or use kernel drivers to register various types of kernel callback routines such as ProcessNotifiyRoutine to detect when a new process is created, and so on.
However, in addition to these well-known mechanisms, some EDRs use more sophisticated and unconventional mechanisms that have been used by the game hacking community for many years.
By looking at these EDRs more closely, by trying to reverse engineer and debug them, some of these detections can be interpreted as some tricky traps for malware influenced by the game hacking community.
In my talk "EDR Analysis: An introduction to reversing sophisticated detection," I will provide insights into how to debug, reverse, and understand these EDR detection mechanisms in detail, as well as how to evade them.