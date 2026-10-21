---
title: Homelab Proxmox
description: Une infrastructure personnelle sous Proxmox pour apprendre l'architecture sécurisée et auto-héberger des services.
importance: 1
category: infrastructure
---

## Présentation

Un homelab personnel sous **Proxmox VE**, pour reproduire une infrastructure proche de celle d'une entreprise et mettre en pratique le durcissement sécurité. Il a un double objectif : apprendre et expérimenter, et héberger mes propres services.

---

## Objectifs

- Concevoir et déployer un **réseau segmenté et durci** de A à Z
- Pratiquer l'infrastructure-as-code avec **Ansible** pour des déploiements reproductibles
- Auto-héberger des services critiques plutôt que dépendre de SaaS tiers
- Expérimenter la détection d'intrusion, la supervision et la réponse à incident

---

## Stack

| Composant | Technologie |
|---|---|
| Hyperviseur | Proxmox VE |
| Conteneurisation | Podman |
| Gestion de configuration | Ansible |
| OS | Debian / Rocky Linux |
| Réseau | Segmentation VLAN (en cours) |

---

## Services hébergés

- **Vaultwarden** — gestionnaire de mots de passe auto-hébergé compatible Bitwarden
- *(d'autres services à venir au fil de l'évolution du lab)*

---

## Ce que j'apprends

- Segmentation réseau et conception de règles de pare-feu
- Durcissement de systèmes Linux (CIS Benchmarks, durcissement SSH, fail2ban)
- Déploiements reproductibles avec des playbooks Ansible
- Sécurité des conteneurs avec Podman (conteneurs rootless)

---

## Statut

🟡 **En cours** — le cœur de l'infrastructure est en place, j'étends activement les services et les contrôles de sécurité.

---

*Ce projet est documenté au fil de sa construction. Les mises à jour seront publiées ici, et peut-être sous forme de writeups détaillés.*
