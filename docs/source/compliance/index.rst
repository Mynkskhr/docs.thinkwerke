Compliance Mapping Overview
===========================

Purpose
-------

This section explains how Thinkwerke approaches **regulatory and compliance requirements**
as **engineering and operational problems**, not documentation exercises.

The focus is on translating regulatory obligations into:

- Clear ownership
- Enforceable technical controls
- Repeatable workflows
- Audit-ready evidence

---

Compliance as an Engineering Discipline
---------------------------------------

In regulated environments, compliance often fails because:

- Controls exist only in policy documents
- Ownership is unclear across teams
- Evidence is collected manually and late
- Engineering teams are blocked during audits and tenders

Thinkwerke treats compliance as a **system design problem**.

Controls must be:

- Implemented in platforms and pipelines
- Observable in day-to-day operations
- Provable at any point in time

---

Regulations Covered
-------------------

This documentation covers practical implementation guidance for:

- ISO/IEC 27001
- NIS2 Directive
- Cyber Resilience Act (CRA)
- GDPR
- Cross-framework mappings and overlaps

Each regulation is addressed individually, then aligned through crosswalks.

---

What “Mapping” Means in Practice
--------------------------------

Compliance mapping connects four layers:

1. Regulatory requirement
2. Internal policy or control objective
3. Technical implementation
4. Evidence and proof

This prevents:

- Overlapping controls
- Conflicting interpretations
- Redundant tooling
- Audit fatigue

---

Evidence by Design
------------------

Evidence is not produced during audits.
It is produced continuously through:

- CI/CD pipelines
- Cloud configurations
- Security workflows
- Operational logs and approvals

This allows organisations to respond to:

- Audits
- Customer security assessments
- Tenders
- Regulatory inquiries

Without disruption.

---

How to Use This Section
-----------------------

Each regulation page follows a consistent structure:

- Regulatory intent and scope
- Key obligations affecting engineering and operations
- Control interpretation for cloud-native environments
- Example implementations
- Evidence expectations

Crosswalk documents show where requirements overlap
to reduce duplication.

---

Audience
--------

This section is written for:

- CISOs and security leaders
- Engineering and platform leads
- Compliance and risk owners
- Audit and assurance teams

The goal is shared understanding and shared ownership.

---

Relationship to Solutions
-------------------------

Compliance mapping relies on the following solution areas:

- :doc:`../solutions/secure-software-lifecycle`
- :doc:`../solutions/vulnerability-lifecycle`
- :doc:`../solutions/cloud-security-foundations`
- :doc:`../solutions/soc-siem-modernisation`
- :doc:`../solutions/cnapp-kubernetes`

Compliance cannot be sustained without these capabilities in place.

---

Key Takeaway
------------

Compliance is not a destination.
It is an **operating capability** that must scale with products,
cloud platforms, and delivery speed.

When controls are engineered correctly,
compliance stops being a blocker and becomes an enabler.



.. toctree::
   :maxdepth: 1

   iso27001
   nis2
   cra
   gdpr
   crosswalks

