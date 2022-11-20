---
title: Bluesmoke Devrandom2
tags: [Vulnhub, CTF, hacking, pentesting]
style: fill
color: success
description: This is my very first video, developing Bluesmoke - Devrandom2 from VulnHub. You'll find vulnerabilities such as Wildcard injection (tar/zip), Abusing SSH keys, Server Side Template Injection (SSTI), hexdump decoding
---

In this machine we found a Backup-as-a-Service (BaaS) server where we can freely upload .tar and .zip files. We abuse a cron job by injecting command arguments as files since it uses a wildcard. Furthermore, to escalate privileges we found a webserver running Jinja2 which is vulnerable to SSTI and once we move laterally, we found a hexdump with rootcreds.


[![Youtube redirect](https://img.youtube.com/vi/vLb0m1xf5Xs/0.jpg)](https://www.youtube.com/watch?v=vLb0m1xf5Xs)


Make sure to subscribe for more!
