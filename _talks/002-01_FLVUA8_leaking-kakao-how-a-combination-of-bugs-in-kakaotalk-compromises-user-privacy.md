---
accepted: true
code: FLVUA8
details: true
keynote: false
layout: talk
speakers:
- bio: Hey. I'm Dawin, yet another security researcher.
  handle: false
  name: stulle123
  photo: ''
timeslot:
  duration: 30
  end: 2024-11-11 10:30:00+01:00
  start: 2024-11-11 10:00:00+01:00
title: 'Leaking Kakao: How a Combination of Bugs in KakaoTalk Compromises User Privacy'
track: 2
---

KakaoTalk is the WhatsApp of South Korea with more than 100 million downloads from the Google Playstore.
In this talk we show how multiple vulnerabilities in a chat app can lead to the disclosure of users' messages.
We start by showing an account takeover "one-click" exploit in KakaoTalk's regular chat room without breaking cryptography or escaping the app's sandbox.
Next, we present how the app's end-to-end encryption feature "Secure Chat" works and discuss a couple of protocol weaknesses.
One of the issues is a well-known server-side MITM attack where Kakao Corp.
can secretly replace public keys without immediate user notification.
We also release our tooling so that fellow security researchers can dig into KakaoTalk's broad attack surface to find more bugs.