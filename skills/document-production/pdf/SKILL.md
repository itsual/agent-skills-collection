---
name: pdf
description: >
  Create, read, and manipulate PDF documents — including reports, forms, invoices, and combined documents — with attention to layout, text extraction, and compatibility.
  Use when the user asks for a PDF, needs to merge/split/rotate PDFs, extract text/tables, or produce a non-editable final deliverable.
---

# PDF – PDF Document Production & Manipulation

## Overview

PDFs are the standard for final, portable documents. Create clean, professional PDFs and handle common manipulation tasks (merge, split, extract, watermark) reliably.

## When to Use

- User requests a PDF deliverable (report, invoice, certificate, ebook, etc.)
- Need to combine, split, or reorder existing PDFs
- Text or table extraction from existing PDFs
- Adding page numbers, watermarks, or simple forms

## Core Capabilities

- Generate well-laid-out PDFs from structured content
- Merge multiple PDFs into one
- Split or extract specific pages
- Rotate pages
- Add simple watermarks or headers/footers
- Extract text and tables (with OCR awareness when needed)
- Preserve or improve accessibility where practical

## Design Principles for Generated PDFs

- Consistent margins and typography
- Clear visual hierarchy
- Sufficient contrast
- Logical reading order
- Embed fonts when necessary for portability
- Avoid unnecessary complexity that breaks across PDF readers

## Verification

- [ ] PDF opens correctly in major readers (Adobe, Preview, browser, etc.)
- [ ] Text is selectable/searchable when expected
- [ ] Layout is intact (no clipped text or overlapping elements)
- [ ] Page count and order are correct after manipulations
- [ ] File size is reasonable for the content

## Common Pitfalls

- Generating PDFs that only look correct in one viewer
- Losing text selectability through unnecessary rasterization
- Forgetting to handle page size and orientation consistently
- Poor handling of existing scanned/image-based PDFs
