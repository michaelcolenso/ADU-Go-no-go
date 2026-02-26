ADU GO / NO-GO

Agentic Build Instructions (Authoritative)

Mission

Build a decision-grade ADU feasibility product that answers, with confidence:

“Should I build an ADU on this property, in this city, using this approach — or stop?”

The product must prevent five-figure mistakes, not educate casually.

⸻

Scope Lock (Non-Negotiable)
	•	One city for v1 (Seattle)
	•	One outcome: Proceed / Stop / Hire Professional
	•	No inspiration, no lifestyle content, no aspirational copy
	•	Decisions > explanations

If a section does not change a decision, delete it.

⸻

Agent Roles & Responsibilities

1. Regulatory Synthesizer

Goal: Convert city code into executable constraints.

Deliverables
	•	research/cities/seattle/*.md

Rules
	•	No prose summaries
	•	Every rule must be testable (IF/THEN)
	•	Ambiguity → flag as risk, not assumption

⸻

2. Decision System Architect

Goal: Produce the feasibility engine.

Deliverables
	•	decision-system/feasibility-tree.md
	•	decision-system/kill-criteria.md

Rules
	•	Binary logic only
	•	Early kill paths preferred
	•	If unsure → STOP outcome, not “maybe”

⸻

3. Cost & Risk Modeler

Goal: Surface hidden cost exposure.

Deliverables
	•	calculators/cost-exposure-model.xlsx
	•	calculators/fee-mapping.md

Rules
	•	Conservative estimates
	•	Uncertain fees flagged as “risk”
	•	Any single item >$10k must be highlighted

⸻

4. Sequence & Playbook Engineer

Goal: Prevent rework and ordering mistakes.

Deliverables
	•	playbook/sequence-of-operations.md
	•	playbook/permit-timeline.md

Rules
	•	Order matters more than completeness
	•	Explicit “DO NOT DO X BEFORE Y” rules required

⸻

5. Adversarial QA Agent

Goal: Protect the user and the product.

Deliverables
	•	qa/adversarial-review.md
	•	qa/user-simulations.md

Rules
	•	Assume user is stressed, inexperienced, literal
	•	Identify where bad interpretation could cost money
	•	Recommend deletion over softening

⸻

Mandatory Self-Improvement Loops

Loop 1 — Decision Consistency

Same inputs → same decision across agents.
Failure = system invalid.

Loop 2 — $20k Mistake Test

Every module must answer:

“What $20k mistake does this prevent?”

No answer → delete module.

Loop 3 — Jurisdiction Drift

Track ordinance changes monthly in:
	•	research/regulatory-change-log.md

Outdated logic is worse than missing logic.

Loop 4 — Adversarial Simulation

Run 10 hostile scenarios:
	•	Tight lots
	•	Financing before permits
	•	Prefab where utilities disallow

Silent failure = hard stop.

⸻

Quality Gates (Ship Blockers)

A section ships only if:
	•	It produces a decision
	•	It cites a specific rule or cost
	•	It reduces uncertainty
	•	It would still be useful even if the user hired a GC

⸻

Build Order (Strict)
	1.	Lock product/scope-lock.md
	2.	Complete Seattle end-to-end
	3.	Run QA simulations
	4.	Freeze decision logic
	5.	Only then add second city

⸻

Definition of Done

The product is done when:
	•	A homeowner can confidently kill a bad ADU idea in under 30 minutes
	•	The system says “stop” more often than “proceed”
	•	No section exists just to be informative

This is not content.
This is decision infrastructure.
