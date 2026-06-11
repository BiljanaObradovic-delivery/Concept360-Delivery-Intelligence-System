# Execution Debt — Layer Map
*Execution Gap Framework · Concept360 · © 2026*

---

Execution debt does not accumulate randomly. Each type maps to specific layers in the Execution Gap Framework — the layers where the work was either skipped, deferred, or treated as someone else's problem.

This document maps five debt types to the layers where they originate and where they are resolved.

---

## Governance debt
**Primary layers: Operating Model (L0) · Post-Launch, Steady State & Continuity (L7)**

Governance debt begins at L0 — when the operating model is approved on paper but ownership is never operationalized. RACI exists as a document. Decision rights are assumed rather than assigned. Escalation paths are implicit.

By L7, the debt has compounded. The delivery team is gone. The operations team inherits a governance structure that was never designed to run without active program management. Vendor SLAs have no enforcement owner. Regulatory reporting has no single accountable role.

*What the framework addresses:* Operating Model design at L0 establishes decision rights, RACI, and escalation ownership before build starts. L7 governance setup ensures these structures survive the transition from delivery to operations.

---

## Compliance debt
**Primary layers: Regulatory & Legal (L1) · Structure & Contracts (L2)**

Compliance debt is the most common and most expensive debt type. It accumulates when regulatory obligations are treated as a gate at the end of the program rather than a sequencing dependency from the start.

At L1, the failure is sequencing: MiCA/CASP obligations, DORA requirements, AML program design, and MLRO appointment arrive late — after architecture decisions have already been made that cannot accommodate them without rework. At L2, the debt materializes in contracts: vendor MSAs that do not reflect regulatory obligations, SLA frameworks without compliance clauses, token classification decisions made without legal sign-off.

*What the framework addresses:* L1 is positioned before technical architecture begins. Compliance is a delivery dependency — not a review at the end.

---

## Vendor dependency debt
**Primary layers: Build & Audit (L4) · Post-Launch, Steady State & Continuity (L7)**

Vendor dependency debt accumulates when vendors are onboarded without governance structure. At L4, the build phase introduces multiple vendors — smart contract auditors, KYC/AML providers, custody infrastructure, banking integration partners — each managing their own SLA, their own definition of a blocker, their own escalation path.

Without a unified vendor governance layer, fragmentation is invisible until it affects a delivery gate. By L7, the debt becomes structural: SLAs with no enforcement mechanism, single points of failure with no fallback, and vendor escalation chains that break under operational pressure.

*What the framework addresses:* Vendor governance structure is established at L2 (MSA, SLA framework) and enforced through L4 and L7. Single escalation ownership is defined before the first vendor goes live.

---

## Operational resilience debt
**Primary layers: Go-Live & Operations (L6) · Post-Launch, Steady State & Continuity (L7)**

Operational resilience debt is the debt that becomes visible only after go-live. At L6, the failure is in hypercare design: go-live completes, hypercare ends on a calendar date rather than a stability threshold, and the handover never produces the incident classification, KPI monitoring, and change management structures needed to sustain operations.

At L7, the consequence is DORA exposure: no incident classification taxonomy, audit evidence created retroactively, ICT risk not continuously monitored, BCP/DRP untested in production conditions.

*What the framework addresses:* L6 gate criteria require operational stability evidence — not just technical go-live confirmation. L7 establishes the steady-state governance structures that DORA and regulatory frameworks require to be continuously operational, not periodically assembled.

---

## Data & control debt
**Primary layers: Integration & Testing (L5) · Regulatory & Legal (L1)**

Data and control debt accumulates when the audit trail is treated as an output rather than a design constraint. At L1, the failure is in not establishing what regulatory reporting will require — PoR baseline, KYC/AML data architecture, audit log structure — before technical decisions are made.

At L5, the debt becomes concrete: end-to-end testing reveals KYC/AML gaps that were not caught earlier, PoR baseline has not been established, reporting without audit trail cannot satisfy regulatory requirements, and UAT uncovers data flows that were never mapped.

*What the framework addresses:* Regulatory reporting requirements are defined at L1 and flow into technical architecture at L3. L5 gate criteria include PoR baseline confirmation and audit trail validation before go-live sign-off is possible.

---

## Summary

| Debt Type | Primary Layer(s) | Where it originates |
|-----------|-----------------|---------------------|
| Governance debt | Operating Model (L0) · Post-Launch (L7) | Ownership not operationalized at start; governance not designed to survive delivery exit |
| Compliance debt | Regulatory & Legal (L1) · Structure & Contracts (L2) | Compliance sequenced as a gate, not a dependency; contracts without regulatory clauses |
| Vendor dependency debt | Build & Audit (L4) · Post-Launch (L7) | No unified vendor governance; SLA without enforcement; fragmentation invisible until gate |
| Operational resilience debt | Go-Live & Operations (L6) · Post-Launch (L7) | Hypercare ends on calendar; incident classification and DORA structures never built |
| Data & control debt | Integration & Testing (L5) · Regulatory & Legal (L1) | Audit trail treated as output; PoR and KYC/AML architecture defined too late |

---

## The pattern

Most execution debt concentrates at two points: **the beginning** (L0–L2, where foundations are set) and **the end** (L6–L7, where operations must sustain what delivery built).

Programs that address both ends — governance before build, and operational continuity before go-live — carry significantly less debt into steady state.

---

*The Execution Gap Assessment maps which of these debt types are active in your program, at which layer, and in what sequence they need to be addressed.*

*→ [Request an assessment briefing](mailto:biljana.obradovic@concept360.rs)*
*→ [Execution Gap Framework — full reference](https://github.com/BiljanaObradovic-delivery/execution-gap-framework)*

