---
title: Ha Natraj
tags: [Vulnhub, CTF, hacking, pentesting]
style: fill
color: dark
description: Ha Natraj was an interesting machine where I learnt about the power of a misconfigured apache config file
---

In Ha Natraj we exploit a Local File Inclusion vulnerability and a log poisoning on SSH auth.log file. With that, we get access and come across an apache2.conf file with the wrong set of permissions assigned, so we can move laterally. Afterwards, pop a shell out of nmap, which has the Sticky Bit set (bad idea)


[![Youtube redirect](https://img.youtube.com/vi/47KEvz96-c8/0.jpg)](https://www.youtube.com/watch?v=47KEvz96-c8)


Make sure to subscribe for more!
