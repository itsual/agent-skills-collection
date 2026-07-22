---
name: email-security
description: >
  Harden email as a control plane — authentication (SPF/DKIM/DMARC), filtering, BEC controls, and secure handling of high-risk messages.
  Use when reducing phishing success, business email compromise, or spoofing risk.
---

# Email Security

## Overview

Email remains a primary attack channel. Technical authentication, filtering, and process controls for financial and data-changing requests reduce successful compromise.

## When to Use

- DMARC enforcement programs
- Anti-phishing gateway tuning
- Business email compromise (BEC) controls
- Executive and finance protection measures

## Core Practices

- Implement SPF, DKIM, and DMARC; move toward reject policy carefully
- Filter malware and phishing with layered gateways and URL rewriting as appropriate
- Protect high-value mailboxes with stronger controls and monitoring
- Require out-of-band verification for payment and account-change requests
- Monitor for mailbox rules that forward or hide mail (post-compromise)
- Educate and enable easy reporting

## Principles

- Lookalike domains and compromised partner email bypass simple intuition
- Process controls for money movement are as important as filters
- DMARC monitor mode forever is incomplete
- External forwarding rules are a common persistence mechanism

## Verification

- [ ] SPF/DKIM/DMARC are correctly configured for primary domains
- [ ] High-risk business processes require secondary verification
- [ ] Suspicious-message reporting path is active
