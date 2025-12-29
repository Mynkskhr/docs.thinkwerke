Control to Proof
================

Purpose
-------

Regulators, auditors, and customers do not accept intent.
They require **provable implementation**.

This document explains how Thinkwerke establishes
a traceable path from:

- Control requirement
- Technical implementation
- Verifiable proof

This model applies across audits, tenders, and customer assurance.

---

Why Control Statements Fail Without Proof
-----------------------------------------

Common failures include:

- Controls described only in policy documents
- Manual evidence assembled during audits
- Screenshots without context or ownership
- Proof that cannot be reproduced later
- Engineering and compliance working in isolation

These gaps increase risk and reduce credibility.

---

Thinkwerke Control Model
------------------------

Thinkwerke implements a **three-layer model**:

1. Control Definition  
2. Control Implementation  
3. Control Proof

Each layer is explicit and linked.

---

1. Control Definition
---------------------

Controls are defined using:

- ISO/IEC 27001 Annex A
- NIS2 obligations
- CRA security requirements
- GDPR principles
- Customer contractual controls

Each control definition includes:

- Control objective
- Scope and applicability
- Responsible owner
- Associated systems and services

Controls are technology-agnostic at this layer.

---

2. Control Implementation
-------------------------

Implementation translates control intent into:

- Cloud configurations
- CI/CD pipeline stages
- Security tooling
- Operational workflows

Examples include:

- IAM policies enforcing least privilege
- Pipeline checks enforcing artifact integrity
- Vulnerability SLAs enforced via workflow automation
- Logging pipelines producing immutable records

Implementations are owned by engineering teams.

---

3. Control Proof
----------------

Proof is **machine-generated wherever possible**.

Valid proof includes:

- Pipeline execution logs
- Tool outputs (SAST, SCA, CSPM, SIEM)
- Configuration snapshots
- Workflow records with timestamps
- Audit trails from ticketing systems

Screenshots are used only as a last resort.

---

Traceability Model
------------------

Each control maintains traceability across:

- Policy reference
- Implementation location
- Evidence source
- Responsible owner
- Review cadence

This allows rapid validation during audits.

---

Evidence Lifecycle
------------------

Evidence is:

- Generated continuously
- Collected automatically
- Versioned and time-bound
- Reviewed periodically
- Archived with retention rules

This avoids last-minute evidence creation.

---

Example: Vulnerability Management
---------------------------------

**Control**  
Vulnerabilities must be identified, assessed, and remediated within defined SLAs.

**Implementation**  
- Continuous scanning in CI/CD
- Triage workflow in ticketing system
- SLA enforcement via automation

**Proof**  
- Scan reports
- Workflow tickets with timestamps
- SLA compliance metrics

---

Applicability to Regulations
----------------------------

The Control-to-Proof model supports:

- ISO/IEC 27001 audits
- NIS2 supervisory reviews
- CRA conformity assessments
- Customer security reviews
- Internal governance reporting

The same evidence set is reused across contexts.

---

Engineering Ownership
---------------------

Engineering teams:

- Own implementations
- Do not manually assemble evidence
- Improve controls through normal delivery work

Compliance teams:

- Validate mappings
- Review evidence completeness
- Interface with auditors

---

Relationship to Other Documents
-------------------------------

This document is foundational to:

- :doc:`security-questionnaires`
- :doc:`tender-packs`
- :doc:`exportable-artifacts`

All evidence artefacts are derived from this model.

---

Key Takeaway
------------

Controls are only credible when proof is continuous,
traceable, and owned.

Thinkwerke ensures that proof exists before it is requested.
