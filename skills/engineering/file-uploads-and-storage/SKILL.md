---
name: file-uploads-and-storage
description: >
  Design secure, scalable file upload and storage flows (direct-to-cloud, validation, access control, lifecycle).
  Use when implementing uploads, downloads, media handling, or object storage integration.
---

# File Uploads and Storage

## Overview

File handling involves security, performance, cost, and user experience trade-offs. Prefer direct-to-storage patterns for larger files.

## When to Use

- Implementing file or image uploads
- Integrating with S3/GCS/Azure Blob or similar
- Reviewing security of existing upload flows

## Key Practices

- Validate file type, size, and content where appropriate
- Prefer pre-signed URLs / direct uploads for large files
- Store metadata in your database; store blobs in object storage
- Apply least-privilege access controls and short-lived credentials
- Plan for virus scanning, image processing, or async pipelines if needed
- Define retention and deletion policies (including GDPR-style erasure)
- Use CDNs for frequently accessed public assets

## Security Checklist

- [ ] Content-type and size limits enforced
- [ ] Files are not executable in dangerous contexts
- [ ] Access is authorized on every download/view
- [ ] Secrets are not required in the browser for private files

## Verification

- Upload and download paths are secure and performant
- Orphaned files and storage costs are manageable
- Deletion/retention works as specified
