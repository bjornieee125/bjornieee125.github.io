---
# Copy to _posts/YYYY-MM-DD-nom-ctf-challenge.md and fill in.
title: "[CTF Name] — Challenge Name"
summary: "Short description of the challenge and what you learned."
date: 2025-01-01 12:00:00 +0100
categories: [web] # filter: web | mobile | forensics | crypto | reverse | pwn | osint | misc
tags: [ctf]
# thumbnail: /assets/img/writeups/ctf-name.png
---

## Challenge Info

| Field | Value |
|---|---|
| **CTF** | CTF Name |
| **Category** | Web |
| **Difficulty** | Easy / Medium / Hard |
| **Points** | 100 |
| **Solved** | ✅ Yes |

---

## Description

> Paste the original challenge description here.

---

## Reconnaissance

What did you observe first? What did you enumerate?

```bash
# example command
nmap -sV -p- target.ctf
```

---

## Vulnerability Analysis

What vulnerability did you identify and why?

---

## Exploitation

Step-by-step exploitation.

```python
# exploit script
import requests

url = "http://target.ctf/vuln"
payload = "..."
r = requests.get(url, params={"q": payload})
print(r.text)
```

---

## Flag

```
CTF{example_flag_here}
```

---

## Key Takeaways

- What did you learn?
- What would you do differently?
- Any interesting resources to share?
