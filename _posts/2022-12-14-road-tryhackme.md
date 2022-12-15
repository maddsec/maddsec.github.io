---
title: Road
tags: [TryHackMe, CTF, hacking, pentesting]
style: fill
color: primary
description: In road we conduct a webapp pentest against a courier system
---

In road we pentest a web application. We're able to exploit an account takeover vulnerability since we were able to change the admin's password. Then the system doesn't validate the type of file that we can upload as a profile picture, so an attacker may upload a php script and achieve remote command execution. To escalate our privileges, we abuse of the LDRELOAD on "sudo -l"


[![Youtube redirect](https://img.youtube.com/vi/B_Ldhx341ho/0.jpg)](https://www.youtube.com/watch?v=B_Ldhx341ho)


Make sure to subscribe for more!
