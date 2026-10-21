---
# À copier vers _posts/AAAA-MM-JJ-nom-ctf-challenge.md puis à compléter.
title: "[Nom du CTF] — Nom du challenge"
summary: "Courte description du challenge et de ce que tu en as retenu."
date: 2025-01-01 12:00:00 +0100
categories: [web] # filtre : web | mobile | forensics | crypto | reverse | pwn | osint | misc
tags: [ctf]
# thumbnail: /assets/img/writeups/nom-ctf.png
---

## Infos du challenge

| Champ | Valeur |
|---|---|
| **CTF** | Nom du CTF |
| **Catégorie** | Web |
| **Difficulté** | Facile / Moyen / Difficile |
| **Points** | 100 |
| **Résolu** | ✅ Oui |

---

## Énoncé

> Colle ici l'énoncé original du challenge.

---

## Reconnaissance

Qu'as-tu observé en premier ? Qu'as-tu énuméré ?

```bash
# exemple de commande
nmap -sV -p- target.ctf
```

---

## Analyse de la vulnérabilité

Quelle vulnérabilité as-tu identifiée, et pourquoi ?

---

## Exploitation

Exploitation étape par étape.

```python
# script d'exploitation
import requests

url = "http://target.ctf/vuln"
payload = "..."
r = requests.get(url, params={"q": payload})
print(r.text)
```

---

## Flag

```
CTF{exemple_de_flag}
```

---

## Ce que j'en retiens

- Qu'as-tu appris ?
- Que ferais-tu différemment ?
- Des ressources intéressantes à partager ?
