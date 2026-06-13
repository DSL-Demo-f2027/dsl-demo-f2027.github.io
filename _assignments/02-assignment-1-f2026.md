---
type: assignment
date: 2026-10-13T23:59:00
title: "Assignment 1 — Foundations (template)"
due_event:
    type: due
    date: 2026-10-13T23:59:00
    description: "Assignment 1 — Foundations (template) due"
---
> **Master template** (lives in the private `Hertie-DSL-Demo` org, marked as a GitHub *template repo*). The provisioner generates one private `assignment-1-<handle>` copy per student into the cohort org.

## Task

Implement a minimal autograd engine and train a 1-layer network on a toy dataset.

1. Complete the TODOs in [`starter.py`](starter.py).
2. Commit and push to `main` — that's your submission (no CLI ceremony; a plain push is the submit).
3. You'll see your score on the commit once autograding is enabled.

## Grading

| Test | Points |
| --- | --- |
| `forward()` correct | 4 |
| `backward()` gradients | 4 |
| trains below loss threshold | 2 |
| **Total** | **10** |

*Autograding is **deferred** in this demo (ADR 0010). When enabled it runs via `.github/workflows/autograde.yml` → Otter-Grader/nbgrader → `result.json`. The shim is already in every generated repo, so turning it on is a config change, not a per-repo edit.*

_Your private `assignment-1-<your-handle>` repo appears in `Hertie-DSL-Demo`'s cohort org once the teaching team provisions it._
