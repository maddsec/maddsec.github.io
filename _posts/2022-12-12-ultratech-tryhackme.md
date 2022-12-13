---
title: UltraTech
tags: [TryHackMe, CTF, hacking, pentesting]
style: fill
color: dark
description: Ultratech is a nice box to practice API enumeration and docker container breakout
---

In Ultratech we find an API endpoint where we find a Remote Command Execution vulnerability. With that, we find a sqlite file where we recover some credentials from and use it to gain the foothold. To get root privileges, we spawn a shell out of a docker image since we have the docker group assigned


[![Youtube redirect](https://img.youtube.com/vi/YPqJgl3kEgM/0.jpg)](https://www.youtube.com/watch?v=YPqJgl3kEgM)


Make sure to subscribe for more!
