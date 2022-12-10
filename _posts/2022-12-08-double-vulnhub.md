---
title: Double
tags: [Vulnhub, CTF, hacking, pentesting]
style: fill
color: info
description: In Double we exploit an LFI and RCE vulnerabilities and abuse a misconfigured Postfix service
---

In this machine we find a LFI vulnerability, and thanks to a misconfigured Postfix service, we can send an email with embedded PHP code to ourselves, effectively getting RCE. Then we escalate our privileges with a binary with SUID, that we can escape from.


[![Youtube redirect](https://img.youtube.com/vi/HIGLljd3_04/0.jpg)](https://www.youtube.com/watch?v=HIGLljd3_04)


Make sure to subscribe for more!
