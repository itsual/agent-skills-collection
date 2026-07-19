---
name: search-design-and-indexing
description: >
  Design search experiences and indexing strategies (full-text, filters, relevance, ranking).
  Use when adding search features, choosing search technology, or improving search quality.
---

# Search Design and Indexing

## Overview

Search is a product feature as much as a technical one. Relevance, latency, and freshness all matter.

## When to Use

- Adding or redesigning search
- Choosing between database LIKE/full-text, dedicated search engines, or vector search
- Improving relevance or performance of existing search

## Key Decisions

- What needs to be searchable (fields, entities, permissions)?
- Indexing strategy and freshness requirements
- Ranking / relevance signals
- Filtering, faceting, and sorting needs
- Handling of permissions and multi-tenant isolation in results
- Typo tolerance, stemming, language support

## Principles

- Start with the user task, not the technology
- Measure search quality (relevance, zero-result rate, latency)
- Keep indexing pipelines observable and recoverable

## Verification

- Common user queries return relevant results
- Permissions are enforced on search results
- Indexing lag and failures are visible
