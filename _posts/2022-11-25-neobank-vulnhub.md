---
title: Neobank
tags: [Vulnhub, CTF, hacking, pentesting]
style: fill
color: secondary
description: In Neobank we break into the account of a customer of the bank to end up finding an RCE vulnerability. Then we make our way to root by abusing a bin set up to be run as root by a local account user.
---

In this machine we craft a python script to bruteforce some bank's user accounts and find a Remote Code Execution vulnerability on the withdrawing functionality. Then we dump the contents of the MySQL database by re-using some hard-coded passwords found on the config files, and end up moving laterally. Lastly, we make use of a binary configured to be run as root by this user, achieving SYSTEM privileges.


[![Youtube redirect](https://img.youtube.com/vi/4ymGWrMbQXU/0.jpg)](https://www.youtube.com/watch?v=4ymGWrMbQXU)


Make sure to subscribe for more!
