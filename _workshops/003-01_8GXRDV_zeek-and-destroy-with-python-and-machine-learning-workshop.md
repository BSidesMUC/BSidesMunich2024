---
accepted: true
code: 8GXRDV
details: true
keynote: false
layout: workshop
speakers:
- bio: "David Szili is a principal consultant at Alzette Information Security, an
    information security consulting company based in Europe. He has more than ten
    years of professional experience in various areas like penetration testing, red
    teaming, security monitoring, security architecture design, incident response,
    digital forensics, and software development. David has two master's degrees, one
    in computer engineering and one in networks and telecommunication, and he has
    a bachelor's degree in electrical engineering. He holds several IT security certifications,
    such as GSE, GSEC, GCFE, GCED, GCIA, GCIH, GCFR, GMON, GCTD, GCDA, GPEN, GNFA,
    GPYC, GMOB, GMLE, GAWN, CCSK, OSCP, OSWP, CAWASP, CRTP, BTL1, and CEH.\r\nHe is
    also a certified instructor at SANS Institute, teaching FOR572: Advanced Network
    Forensics and FOR509: Enterprise Cloud Forensics and Incident Response, and he
    is the lead author of SANS DFIR NetWars. David regularly speaks at international
    conferences like BruCON, Hack.lu, Hacktivity, x33fcon, Nuit du Hack, BSides London,
    BSides Munich, BSides Stuttgart, BSidesLjubljana, BSidesBUD, BSides Luxembourg,
    Pass the SALT, Black Alps, Security Session, Future Soldier, SANS @Night Talks,
    Meetups, and he is a former member of the organizer team of the Security BSides
    Luxembourg conference."
  handle: false
  name: David Szili
  photo: https://pretalx.com/media/avatars/PTRYM8_aIQKnqK.png
timeslot:
  duration: 240
  end: 2024-11-09 13:00:00+01:00
  start: 2024-11-09 09:00:00+01:00
title: Zeek and Destroy with Python and Machine Learning Workshop
track: 3
---

Zeek is an open-source network security monitor (NSM) and analytics platform that has been around for quite some time (since the mid-90s).
It is used at large university campuses and research labs, but in the past few years, more and more security professionals in the industry have turned their attention to this fantastic tool.

But Zeek is so much more than just a NIDS generating alerts (notices) and log files! Zeek's scripting language allows security analysts to perform arbitrary analysis tasks such as extracting files from sessions, detecting brute-force attacks, or, most importantly, interfacing with external sources, such as Python! The Zeek Python bindings allow us, the analysts, to use powerful Python libraries such as Numpy, Pandas, and Tensorflow and apply machine learning-based detection on network traffic.

During this two-hour workshop, we will learn about the following topics:
- Super fast introduction to Zeek (architecture, events, logs, signatures, etc.)
- Using machine learning and data science tools on Zeek logs (as an example, we will use Fourier Analysis to detect C2 beaconing)
- Super fast crash course in Zeek scripting (just enough to understand how to create new logs)
- Connecting Zeek and Python via the Zeek Broker Communication Framework
- Using machine learning tools in Python on the data we receive from Zeek for detection (as an example, we will use convolutional neural network and random forest models to compare them, and then use them to find unknown malware in live network traffic)

Requirements for the workshop:
- A laptop with at least 16 GB of RAM and more than 50 GB of free disk space (VT-x support must be enabled on the host system).
- Application to run Virtual Images (type-2 hypervisor): VMWare Workstation Pro (recommended), VMWare Workstation Player, VMWare Fusion, or VirtualBox.
- Only 64-bit Intel-compatible (Intel or AMD) processors are supported.
WARNING: ARM-based (like Apple Silicon, Qualcomm Snapdragon, some Microsoft Surface laptops) devices cannot perform the necessary virtualization and therefore cannot be used for the workshop.