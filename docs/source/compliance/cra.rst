Cyber Resilience Act (CRA): Product & Software Engineering
==========================================================

Purpose
-------

This document explains how Thinkwerke interprets and implements the
**EU Cyber Resilience Act (CRA)** for software products and
vendor-hosted digital services.

The focus is on **engineering secure-by-design products**,
establishing **defensible vulnerability handling**, and producing
**continuous, audit-ready evidence**.

---

What the CRA Actually Targets
-----------------------------

The CRA applies to products with digital elements, including:

- Software products
- Cloud-hosted platforms and services
- Embedded and connected systems
- Products distributed to EU markets

Its intent is to ensure that security is built into products
**throughout their lifecycle**, not added post-release.

---

Core CRA Expectations
---------------------

CRA introduces explicit expectations around:

- Secure development practices
- Vulnerability management
- Software supply-chain transparency
- Timely remediation and disclosure
- Accountability of manufacturers and vendors

These expectations directly affect engineering teams.

---

Common Failure Patterns
-----------------------

CRA initiatives often stall because:

- Security is treated as a legal requirement only
- SBOMs are generated but not governed
- Vulnerability handling lacks ownership and SLAs
- CI/CD pipelines are excluded from compliance scope
- Evidence cannot be produced consistently

Thinkwerke addresses CRA at system-design level.

---

Thinkwerke Implementation Model
-------------------------------

CRA compliance is implemented across four layers:

1. Secure software lifecycle (SSLM)
2. Vulnerability intake, triage, and remediation
3. Supply-chain governance (SBOM & OSS)
4. Continuous evidence and reporting

Each layer is traceable and auditable.

---

Secure Software Lifecycle (SSLM)
--------------------------------

CRA-aligned SSLM includes:

- Secure CI/CD pipelines
- Static, dynamic, and dependency analysis
- Artifact integrity and provenance
- Policy enforcement before release

Security controls are embedded where code is built and shipped.

---

Vulnerability Handling
----------------------

CRA-compliant vulnerability management includes:

- Centralised intake of vulnerabilities
- Ownership and severity-based SLAs
- Engineering workflows (e.g. issue tracking)
- Verification of remediation
- Evidence of timelines and actions

This applies to both internally found and externally reported issues.

---

Software Supply-Chain Governance
--------------------------------

CRA requires visibility and control over dependencies.

Thinkwerke implementations include:

- SBOM generation and versioning
- OSS license identification and tracking
- Risk classification of components
- Change impact visibility across releases

SBOMs are treated as living artefacts, not static exports.

---

Vendor-Hosted Responsibility
-----------------------------

For cloud-hosted products, CRA responsibilities extend beyond code:

- Platform security configurations
- Runtime monitoring
- Incident handling
- Patch and update processes

Shared responsibility models are documented and evidenced.

---

Evidence and Audit Readiness
----------------------------

CRA evidence is generated continuously via:

- CI/CD execution logs
- Vulnerability workflow records
- SBOM history and approvals
- Release and change records

This supports regulatory review, customer assurance, and market access.

---

Relationship to Other Frameworks
--------------------------------

CRA overlaps with:

- ISO 27001 technical controls
- NIS2 operational resilience requirements
- Customer security assessments

See also:

- :doc:`iso27001`
- :doc:`nis2`
- :doc:`crosswalks`

---

Key Takeaway
------------

CRA compliance is achieved by **engineering discipline**, not paperwork.

When secure development, vulnerability handling,
and supply-chain governance are built into delivery,
CRA becomes sustainable and provable.

