---
name: ot-ics-security-basics
description: >
  Apply foundational OT/ICS security awareness — segmentation, safe change, vendor remote access, and availability-first constraints.
  Use when IT/OT boundaries exist, or when securing industrial and operational technology environments at a basic program level.
---

# OT / ICS Security Basics

## Overview

Operational technology prioritizes safety and availability differently from typical IT. Controls must respect process uptime, legacy systems, and physical consequences.

## When to Use

- IT/OT network boundary design
- Vendor remote access into plants or facilities
- Basic OT asset inventory and patch strategy
- Bridging IT security teams into OT contexts

## Core Practices

- Inventory OT assets and data flows across the IT/OT boundary
- Segment OT networks; control and monitor conduits
- Manage vendor remote access tightly (time-bound, monitored)
- Patch and change with process-safety awareness
- Prefer passive monitoring where active scanning is risky
- Coordinate incident response with operations and safety roles

## Principles

- “Just scan it like IT” can cause outages or safety issues
- Availability and safety may outrank confidentiality in prioritization
- Legacy embedded devices often cannot run modern agents
- Physical access is part of the threat model

## Verification

- [ ] IT/OT boundary and conduits are documented
- [ ] Vendor access is controlled and reviewed
- [ ] OT changes follow an appropriate change process
