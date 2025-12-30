Vendor-Hosted Responsibility 
Clarifying Ownership in Cloud & Managed Environments
====================================================

From Assumed Trust to Defensible Accountability
-----------------------------------------------

Purpose
-------

This whitepaper explains how organisations operating in **vendor-hosted**
and **managed cloud environments** can establish **clear, defensible security
and compliance responsibility**.

It addresses one of the most common failure points in audits, tenders, and
customer assurance: **unclear shared responsibility**.

---

The Reality of Vendor-Hosted Environments
-----------------------------------------

Modern systems increasingly rely on:

- Public cloud platforms
- Managed Kubernetes services
- SaaS and PaaS components
- Third-party security tooling

While vendors provide strong baseline security, **responsibility does not
disappear**.

Regulators, auditors, and customers consistently expect organisations to
demonstrate:

- What they own
- What they inherit
- How inherited controls are validated
- How gaps are mitigated

---

The Shared Responsibility Model — and Its Limits
------------------------------------------------

Cloud providers publish shared responsibility models describing:

- Provider responsibilities (e.g. physical security, platform integrity)
- Customer responsibilities (e.g. configuration, access, data protection)

However, these models are:

- High-level
- Provider-centric
- Not audit-ready on their own

Organisations must **operationalise** shared responsibility for their
specific architecture and use cases.

---

Responsibility Categories
-------------------------

A defensible model separates responsibilities into three categories:

### Customer-Owned Controls

Controls fully implemented and operated by the organisation, such as:

- Identity and access management
- Secure configuration
- Change management
- Application security
- Vulnerability remediation

These require **direct technical evidence**.

---

### Vendor-Provided Controls

Controls delivered by the vendor, including:

- Physical data centre security
- Platform patching
- Infrastructure resilience
- Managed service security features

These require **validated assurance**, not blind trust.

---

### Shared Controls

Controls where responsibility is split, for example:

- Logging and monitoring
- Backup and recovery
- Incident detection and response
- Network segmentation

Shared controls are the most common source of audit findings when ownership
is not explicitly defined.

---

From Responsibility to Evidence
-------------------------------

Clear responsibility is not sufficient on its own.

Organisations must demonstrate:

- Which control objectives apply
- How responsibility is allocated
- What evidence exists
- How evidence is maintained over time

Typical evidence sources include:

- Cloud configuration states
- IAM policies and access reviews
- Logging and monitoring outputs
- Vendor attestations and certifications
- Internal validation checks

---

Validating Vendor Controls
--------------------------

Vendor claims must be **validated**, not assumed.

Validation methods include:

- Reviewing vendor compliance reports (e.g. ISO 27001, SOC 2)
- Mapping vendor controls to internal control objectives
- Performing configuration validation
- Monitoring service-level indicators
- Testing inherited security features

Validation results should be documented and traceable.

---

Regulatory Expectations
-----------------------

Regulations such as:

- ISO/IEC 27001
- NIS2
- CRA
- DORA
- GDPR

Do not accept “the vendor handles it” as a control strategy.

They require organisations to:

- Retain accountability
- Demonstrate oversight
- Prove effectiveness
- Respond to failures

Vendor-hosted environments **increase**, not reduce, governance expectations.

---

Common Failure Patterns
-----------------------

Audits and customer reviews frequently identify:

- Unclear ownership of shared controls
- Over-reliance on vendor marketing claims
- Missing validation of inherited controls
- Inconsistent narratives between teams
- Evidence assembled manually at the last minute

These issues create avoidable risk.

---

A Practical Operating Model
---------------------------

A mature vendor-hosted responsibility model includes:

1. Explicit responsibility mapping per control
2. Clear ownership and escalation paths
3. Continuous validation of inherited controls
4. Evidence generation embedded into operations
5. Reusable narratives for audits and customers

This model supports scale, resilience, and trust.

---

Relationship to Other Materials
-------------------------------

This whitepaper is supported by:

- :doc:`/solutions/cloud-security-foundations`
- :doc:`/solutions/cnapp-kubernetes`
- :doc:`/compliance/iso27001`
- :doc:`/compliance/nis2`
- :doc:`/evidence-library/control-to-proof`

---

Key Takeaway
------------

Vendor-hosted environments do not remove responsibility.

They require **clear ownership, validated inheritance, and continuous proof**
to withstand regulatory, audit, and customer scrutiny.


