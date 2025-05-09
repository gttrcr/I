---
title: hashcat to hack a keepass2 kdbx
date: 2025-04-23
permalink: /posts/2025/04/23
tags:
   - Computer science
---

```bash
hashcat -a 3 --stdout -1 "abcRH&3h" ?1what_you_know?l?s?a > candidates.txt
hashcat -m 13400 -a 0 -o cracked_password.txt hash.txt candidates.txt --status --status-timer=2 --potfile-disable
```
1. `candidates.txt` file is produced containing strings that match the given structure `?1what_you_know?l?s?a`.
2. `candidates.txt` file is used for a dictionary attach on the `hash.txt` file computed from the kdbx keepass2 file in websites like [https://keepass2john.com/](https://keepass2john.com/).
3. Any cracked password will be saved in the `cracked_password.txt` file