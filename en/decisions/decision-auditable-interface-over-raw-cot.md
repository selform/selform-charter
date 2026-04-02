[中文版本](../../zh/decisions/decision-auditable-interface-over-raw-cot.md)
Status: draft
Last updated: 2026-04-02

# Decision: Prefer an auditable reasoning interface over raw chain-of-thought
- Decision: Require Selform to provide an auditable reasoning interface (facts, assumptions, key inferences, counter-views, uncertainty, and normative commitments) rather than exposing raw, stream-of-consciousness internal chains.
- Date: 2026-04-02
- Context: “Show the full chain-of-thought” can create a false trust signal (“it’s long, so it’s true”) and still hides normative choices behind narrative structure.
- Options considered:
  - Mandate raw chain-of-thought disclosure.
  - Mandate an auditable interface that makes premises and value-ordering explicit without claiming neutrality.
- Rationale: The goal is not “no stance,” but stance made inspectable; auditability preserves refusal rights and reduces narrative manipulation.
- Impact: Docs and governance should specify the interface fields and treat omissions as a safety failure.
- Follow-up: Define minimal required audit fields and how they are logged/reviewed.

