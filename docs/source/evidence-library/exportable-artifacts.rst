Exportable Artifacts
===================

Purpose
-------

Exportable artifacts are the **final, consumable outputs**
used for audits, tenders, customer assurance, and regulatory review.

This document explains:

- What qualifies as an exportable artifact
- How artifacts are produced from live systems
- How they remain reusable across multiple contexts

---

What Is an Exportable Artifact
------------------------------

An exportable artifact is:

- Derived from implemented controls
- Backed by verifiable proof
- Contextualised for external review
- Reusable across audits and customers

Artifacts are **not** manually created reports.
They are structured outputs generated from systems and workflows.

---

Common Artifact Types
---------------------

Thinkwerke artifacts typically include:

- Evidence packs for tenders
- Audit-ready control mappings
- Security questionnaire responses
- Architecture and responsibility narratives
- Metrics and dashboards
- Workflow and ticket exports

Each artifact references live evidence sources.

---

Artifact Design Principles
--------------------------

Exportable artifacts follow strict principles:

- Traceable to controls
- Linked to implementation
- Time-bound and versioned
- Reviewable without internal system access
- Understandable by non-engineers

Artifacts must survive external scrutiny.

---

Artifact Generation Model
-------------------------

Artifacts are generated from:

- CI/CD pipelines
- Cloud configuration state
- Security tooling outputs
- Workflow systems
- Governance repositories

The generation process is repeatable.

---

Example: Tender Evidence Pack
-----------------------------

A typical tender pack includes:

- Control coverage summary
- Architecture overview
- Shared responsibility mapping
- Evidence references per control
- SLA and vulnerability metrics

The same pack can be reused across multiple bids.

---

Example: Audit Artifact
-----------------------

Audit artifacts include:

- Control-to-proof mappings
- Evidence snapshots
- Ownership records
- Review logs

Auditors can validate controls without ad-hoc requests.

---

Versioning and Retention
------------------------

Artifacts are:

- Versioned per audit or customer
- Stored with retention rules
- Traceable to underlying evidence timestamps

Historical artifacts remain available.

---

Reusability Across Contexts
---------------------------

One artifact set supports:

- ISO/IEC 27001 audits
- NIS2 supervisory requests
- CRA conformity assessments
- Customer security reviews
- Procurement processes

This reduces duplication and effort.

---

Roles and Responsibilities
--------------------------

Engineering teams:

- Generate evidence automatically
- Do not assemble artifacts manually

Security and compliance teams:

- Validate completeness
- Maintain mappings
- Approve releases

Leadership teams:

- Use artifacts for assurance and decision-making

---

Relationship to Other Documents
-------------------------------

This document builds on:

- :doc:`control-to-proof`
- :doc:`tender-packs`
- :doc:`security-questionnaires`

Artifacts are the output layer of the evidence system.

---

Key Takeaway
------------

Exportable artifacts are not reports.
They are **proof, structured for trust**.

Thinkwerke ensures artifacts are always ready
before they are requested.
