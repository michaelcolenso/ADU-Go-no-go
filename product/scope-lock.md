# Scope Lock — ADU Go/No-Go v1

## Purpose
This document defines the non-negotiable scope for v1 of the ADU decision product.
If any implementation detail conflicts with this file, this file wins.

## Jurisdiction (Locked)
- **City:** Seattle only.
- **Rule:** IF property jurisdiction is not Seattle THEN output = **STOP**.

## Decision Outcomes (Locked)
Only the following outcomes are allowed:
1. **PROCEED**
2. **STOP**
3. **HIRE PROFESSIONAL**

- **Rule:** IF an output label is not one of the three approved outcomes THEN implementation is non-compliant and must be rejected.

## Product Intent (Locked)
- This is **decision infrastructure**, not educational or inspirational content.
- Every included module must directly change or defend a decision.

- **Rule:** IF a section does not alter a decision path, reduce uncertainty, or prevent a costly mistake THEN delete the section.

## Explicit Exclusions
The following are out of scope for v1:
- Lifestyle storytelling
- Interior design inspiration
- Neighborhood marketing copy
- Aspirational ADU content
- General real-estate education not tied to a decision gate

- **Rule:** IF content is primarily informational and not decision-driving THEN remove before ship.

## Data and Logic Guardrails
- Binary logic preferred.
- Early kill paths preferred.
- Ambiguity must be treated as risk.

- **Rule:** IF a critical decision input is ambiguous or unresolved THEN output must default to **STOP** or **HIRE PROFESSIONAL** (never optimistic proceed-by-default).

## Expansion Freeze
v1 must complete Seattle end-to-end before any expansion.

- **Rule:** IF Seattle artifacts are incomplete (research, decision-system, calculators, playbook, QA) THEN adding a second city is prohibited.

## Change Control
Any scope expansion requires explicit approval recorded in this file.

Required fields for an approved change:
- Date
- Requestor
- Proposed change
- Risk introduced
- Decision impact
- Approval record

Until an entry is recorded, scope remains locked as written above.
