---
layout: page
title: Proxmox Homelab
description: A personal Proxmox-based infrastructure for learning secure architecture and self-hosting services.
img: assets/img/projects/homelab.jpg
importance: 1
category: infrastructure
---

## Overview

A personal homelab built on **Proxmox VE** to simulate realistic enterprise-grade infrastructure and explore security hardening in practice. The lab serves a dual purpose: learning and experimentation, as well as hosting self-managed services.

---

## Goals

- Design and implement a **segmented, hardened network** from scratch
- Practice infrastructure-as-code with **Ansible** for reproducibility
- Self-host critical services to avoid relying on third-party SaaS
- Experiment with intrusion detection, monitoring, and incident response

---

## Stack

| Component | Technology |
|---|---|
| Hypervisor | Proxmox VE |
| Containerization | Podman |
| Config management | Ansible |
| OS | Debian / Rocky Linux |
| Network | VLAN segmentation (in progress) |

---

## Hosted Services

- **Vaultwarden** — Self-hosted Bitwarden-compatible password manager
- *(More services coming as the lab grows)*

---

## What I'm learning

- Network segmentation and firewall rule design
- Hardening Linux systems (CIS Benchmarks, SSH hardening, fail2ban)
- Reproducible deployments with Ansible playbooks
- Container security with Podman (rootless containers)

---

## Status

🟡 **In progress** — Core infrastructure up, actively expanding services and security controls.

---

*This project is documented as I build it. Updates will be posted here and potentially as detailed write-ups.*
