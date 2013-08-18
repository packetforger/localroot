Local Root Exploit Toolkit
=========

This toolkit is designed for when you have a non interactive shell on a 
box and wish to pop root on it. For example, when you have gained a 
webshell on it, but no backconnect. It drops a suid root shell (named 
suid) in the current working directory. You simply do ./suid (command) 
to execute a command as root.

It is an ongoing work in progress, and is intended to serve only as an 
example. Seriously, running the "auto.pl" script is likely the fastest 
way to get a kernelpanic to happen, as it is in no way "intelligent".

It is based almost entirely on previous work by Pashkela from RDOT.ORG,
and the Enlightenment framework by Spender. All I am doing is gathering
the scripts together, filling in the blanks, and providing some wrapper
scripts for automated exploitation in a somewhat-blind fashion.

Exploits Implemented:
======

* Linux PERF_EVENTS 

Bitcoins: 1MJ6KnLdXm82UjdDuvgjxDhngLjBMJfamV
