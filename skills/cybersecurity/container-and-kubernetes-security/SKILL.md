---
name: container-and-kubernetes-security
description: >
  Secure containers and Kubernetes — image hygiene, runtime least privilege, network policies, and cluster hardening.
  Use when deploying containerized workloads or reviewing K8s security posture.
---

# Container and Kubernetes Security

## Overview

Containers and orchestrators introduce image supply chain, cluster control-plane, and workload isolation concerns. Security must cover build, deploy, and runtime.

## When to Use

- Container CI/CD hardening
- Kubernetes cluster and workload reviews
- Image vulnerability and provenance controls
- Runtime policy and network segmentation in clusters

## Core Practices

- Scan and sign images; use minimal trusted bases
- Run as non-root; drop unnecessary capabilities
- Apply network policies and restrict service exposure
- Harden cluster API access and RBAC
- Manage secrets via dedicated mechanisms, not env in plain YAML casually
- Monitor runtime anomalies and admission controls

## Principles

- A vulnerable image shipped fast is still vulnerable
- Cluster-admin sprawl is as dangerous as domain admin sprawl
- Network flatness inside clusters enables lateral movement
- Supply chain of base images is part of your risk

## Verification

- [ ] Images are scanned and admission policies exist for critical clusters
- [ ] RBAC is least-privilege for humans and service accounts
- [ ] Workloads avoid privileged mode unless justified
