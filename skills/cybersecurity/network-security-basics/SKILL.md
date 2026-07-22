---
name: network-security-basics
description: >
  Apply network security basics — segmentation, firewalls, secure remote access, and exposure minimization — to reduce lateral movement and attack surface.
  Use when designing network architecture, reviewing cloud/network controls, or hardening perimeter and internal paths.
---

# Network Security Basics

## Overview

Network security limits who can reach what. Segmentation and exposure control slow attackers and contain blast radius when endpoints fall.

## When to Use

- Network and cloud network design reviews
- Firewall and security group policy design
- Remote access (VPN/ZTNA) architecture
- Reducing unnecessary internet exposure

## Core Practices

- Segment networks by trust and function
- Deny by default; allow explicitly
- Minimize public exposure of management interfaces
- Encrypt sensitive traffic in transit
- Prefer modern remote access patterns over flat VPN-to-everywhere
- Log and monitor perimeter and east-west critical paths

## Principles

- Flat networks make every breach a potential catastrophe
- “Temporary” open rules become permanent without review
- Cloud security groups are network controls — treat them as such
- Zero trust is a direction, not a product purchase alone

## Verification

- [ ] Critical systems are segmented from general access
- [ ] Public exposure is inventoried and justified
- [ ] Remote access paths are controlled and monitored
