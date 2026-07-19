---
name: code-review-and-quality
description: >
  Conduct multi-axis code review covering correctness, readability, architecture, security, and performance.
  Use before merging any change, after implementing a feature, when reviewing code written by yourself, another agent, or a human, or when assessing overall code quality.
  Trigger on any request involving code review, PR review, quality check, or "review this change".
---

# Code Review and Quality

## Overview

Multi-dimensional code review with clear quality gates. Every meaningful change should be reviewed before it enters the main branch.

**Approval standard**: Approve a change when it clearly improves overall code health, even if it is not perfect. Perfect code does not exist. The goal is continuous improvement.

## When to Use

- Before merging any PR or significant change
- After completing a feature or bug fix
- When another agent or model produced code that needs evaluation
- During refactoring
- When asked to "review this", "check quality", or "is this good to merge?"

## The Five-Axis Review

Evaluate every change across these dimensions:

### 1. Correctness
Does the code do what it claims?
- Matches the spec or stated requirements?
- Edge cases handled (null, empty, boundaries)?
- Error paths handled (not only happy path)?
- Tests actually verify the right behavior?
- Off-by-one, race conditions, or state bugs?

### 2. Readability & Simplicity
Can another engineer (or agent) understand this without the author explaining it?
- Clear, consistent naming?
- Straightforward control flow?
- Appropriate level of abstraction (not over-engineered)?
- Could this be done in significantly fewer lines?
- Dead code, leftover comments, or temporary hacks?

### 3. Architecture
Does the change fit the system?
- Follows existing patterns or introduces a justified new one?
- Clean module boundaries?
- Dependencies flowing in the right direction?
- Feature-specific logic kept out of shared modules?
- Complexity reduced rather than merely relocated?

### 4. Security
- Input validated and sanitized at boundaries?
- Secrets kept out of code, logs, and commits?
- AuthZ checks present where needed?
- No injection risks (SQL, command, XSS, etc.)?
- External data treated as untrusted?

### 5. Performance
- N+1 queries or unbounded operations?
- Unnecessary work in hot paths?
- Missing pagination on lists?
- Synchronous work that should be async?

## Review Process

1. **Understand context** – What is this change trying to achieve?
2. **Review tests first** – Do they exist and test behavior (not just implementation)?
3. **Walk the implementation** using the five axes.
4. **Categorize findings**:
   - **Critical** – Blocks merge (security, data loss, broken functionality)
   - Required (no prefix) – Must fix before merge
   - **Nit** / Optional – Style or preference
   - **FYI** – Informational only
5. **Verify the verification** – What tests were run? Build status? Manual checks?

## Change Sizing Guidance

- ~100 lines changed → Ideal
- ~300 lines → Acceptable if single logical change
- ~1000+ lines → Usually too large; ask to split

Prefer small, focused changes. Separate refactoring from feature work.

## Common Rationalizations to Reject

| Rationalization | Reality |
|-----------------|--------|
| "It works, that's enough" | Working but unreadable/insecure/architecturally wrong creates debt. |
| "We'll clean it up later" | Later rarely comes. Require cleanup now. |
| "AI-generated code is probably fine" | AI code needs *more* scrutiny, not less. |
| "The tests pass" | Necessary but not sufficient. |

## Verification Checklist

- [ ] All Critical and Required issues resolved
- [ ] Tests pass and cover the change
- [ ] Build succeeds
- [ ] No secrets or sensitive data introduced
- [ ] Complexity has not increased without justification

## See Also

- `security-and-hardening` for deeper security review
- `code-simplification` for focused complexity reduction
- `test-driven-development` for test quality
