# Execution Debt — Layer Map
*Execution Gap Framework · Concept360 · © 2026*

---

Execution debt does not accumulate randomly. Each type maps to specific layers where the work was skipped, deferred, or treated as someone else's problem.

Five debt types. Each has a primary layer. Each has a visible symptom before it becomes an expensive problem.

---

## Governance debt
**Primary layers: L0 · L7**

Ownership assumed rather than assigned. RACI exists as a document. Escalation paths are implicit. By post-launch, the delivery team is gone and operations inherits a governance structure that was never designed to run without active program management.

*Visible symptom:* No named individual accountable for regulatory reporting. Vendor SLA breaches with no clear escalation owner.

---

## Compliance debt
**Primary layers: L1 · L2**

Regulatory obligations treated as a gate at the end rather than a sequencing dependency from the start. MiCA/CASP, DORA, AML program design arrive after architecture decisions have already been made.

*Visible symptom:* Compliance review triggers rework at L3–L4. Vendor contracts without regulatory clauses discovered late.

---

## Vendor dependency debt
**Primary layers: L4 · L7**

Multiple vendors onboarded without unified governance. Each manages its own SLA, its own escalation path, its own definition of a blocker. Fragmentation is invisible until it affects a delivery gate.

*Visible symptom:* SLA breaches unresolved for weeks. No single escalation owner across vendor stack.

---

## Operational resilience debt
**Primary layers: L6 · L7**

Hypercare ends on a calendar date rather than a stability threshold. Incident classification, KPI monitoring, and change management structures never built into operations.

*Visible symptom:* First regulatory audit after go-live finds DORA gaps. BCP untested in production conditions.

---

## Data & control debt
**Primary layers: L1 · L5**

Audit trail treated as an output rather than a design constraint. PoR baseline, KYC/AML data architecture, and audit log structure defined too late to flow into technical decisions.

*Visible symptom:* UAT reveals KYC/AML gaps not caught earlier. Reporting without audit trail cannot satisfy regulatory requirements.

---

## Summary

| Debt Type | Primary Layer(s) | Visible symptom |
|-----------|-----------------|-----------------|
| Governance debt | L0 · L7 | No named owner for regulatory reporting or vendor escalation |
| Compliance debt | L1 · L2 | Compliance triggers rework after architecture is set |
| Vendor dependency debt | L4 · L7 | SLA breaches unresolved, no unified escalation path |
| Operational resilience debt | L6 · L7 | DORA gaps found at first post-launch audit |
| Data & control debt | L1 · L5 | Audit trail incomplete; KYC/AML gaps surface at UAT |

---

Most execution debt concentrates at two points: the beginning (L0–L2) and the end (L6–L7).

The full debt analysis — including layer-by-layer origination, cascade effects, and remediation sequencing — is available through the Execution Gap Assessment.

---

*→ [Request an assessment briefing](mailto:biljana.obradovic@concept360.rs)*
*→ [Execution Gap Framework — full reference](https://github.com/BiljanaObradovic-delivery/execution-gap-framework)*

