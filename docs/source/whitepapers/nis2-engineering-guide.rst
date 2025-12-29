NIS2 Engineering Guide
======================

From Directive to Defensible Implementation
-------------------------------------------

Purpose
-------

This whitepaper explains how the **NIS2 Directive** translates into
**concrete engineering, operational, and governance requirements**
for organisations operating in regulated and critical sectors.

It is not a legal interpretation.
It is an **engineering and operating model guide**.

---

What NIS2 Actually Changes
--------------------------

NIS2 shifts cybersecurity from:

- compliance-as-documentation
- security-as-a-policy exercise

to:

- **continuous risk management**
- **executive accountability**
- **provable operational controls**

Key changes introduced by NIS2 include:

- Mandatory risk-based security measures
- Explicit management accountability
- Incident handling and reporting obligations
- Supply-chain and vendor risk management
- Enforcement backed by penalties and audits

---

Engineering-Centric Interpretation
----------------------------------

From an engineering perspective, NIS2 requires organisations to:

- Implement controls, not just define them
- Produce **evidence continuously**, not retrospectively
- Demonstrate ownership across cloud and vendor-hosted environments
- Align security controls with real system architectures

This means NIS2 compliance must be built into:

- Cloud platforms
- CI/CD pipelines
- Software delivery processes
- Incident and vulnerability workflows

---

Core Engineering Domains Affected
---------------------------------

NIS2 directly impacts the following technical domains:

### Secure Software Lifecycle (SSLM)

- Secure CI/CD pipelines
- Dependency and supply-chain controls
- Vulnerability discovery, prioritisation, and remediation
- Traceable change management

### Cloud & Platform Security

- Identity and access governance
- Logging, monitoring, and detection
- Segmentation and least privilege
- Platform hardening and posture management

### Incident & Crisis Management

- Detect → assess → respond workflows
- Evidence-backed incident reporting
- Integration with SOC and CSIRT operations
- Executive visibility and escalation paths

### Supply-Chain Risk

- Third-party and vendor dependencies
- OSS and component risk tracking
- Contractual security expectations
- Proof of due diligence

---

Risk Management as an Operating Model
-------------------------------------

NIS2 requires **risk management**, not checklist compliance.

In practice this means:

- Defined risk ownership
- Measurable control effectiveness
- Continuous reassessment
- Executive decision-making based on risk signals

Engineering teams must provide:

- Telemetry
- Metrics
- Evidence
- Impact analysis

Leadership must provide:

- Direction
- Prioritisation
- Accountability

---

Evidence Expectations
---------------------

Auditors and regulators will expect evidence showing:

- Controls are implemented
- Controls are operating
- Controls are effective

Examples include:

- CI/CD pipeline outputs
- Vulnerability lifecycle records
- Incident response timelines
- Access review artefacts
- Cloud configuration snapshots

Evidence must be:

- Repeatable
- Timestamped
- Traceable to systems
- Aligned to risk statements

---

Vendor-Hosted & Shared Responsibility
-------------------------------------

Most NIS2-scoped organisations operate on:

- Public cloud
- Managed platforms
- SaaS dependencies

This introduces shared responsibility challenges.

NIS2 does **not** allow responsibility to be outsourced.

Organisations must demonstrate:

- What the vendor provides
- What the organisation owns
- How ownership is enforced
- How effectiveness is proven

This requires explicit mapping between:

- NIS2 requirements
- Cloud services
- Internal controls
- Evidence sources

---

Management Accountability
-------------------------

NIS2 explicitly places accountability on senior management.

From an engineering standpoint, this means:

- Security posture must be visible to leadership
- Decisions must be supported by data
- Risks must be clearly articulated
- Trade-offs must be documented

Dashboards, reports, and metrics must be:

- Accurate
- Actionable
- Decision-grade

---

Common Failure Patterns
-----------------------

Organisations struggle with NIS2 when:

- Compliance is treated as a one-off project
- Controls exist only in documentation
- Evidence is assembled manually
- Engineering and governance are disconnected
- Cloud responsibilities are unclear

These patterns increase audit risk and operational friction.

---

A Practical Path Forward
------------------------

A defensible NIS2 implementation typically involves:

1. Translating NIS2 requirements into technical control objectives
2. Mapping controls to real architectures and pipelines
3. Embedding evidence generation into normal operations
4. Establishing clear ownership across teams
5. Aligning reporting to executive decision needs

---

Relationship to Other Materials
-------------------------------

This whitepaper is supported by:

- :doc:`/solutions/secure-software-lifecycle`
- :doc:`/solutions/vulnerability-lifecycle`
- :doc:`/compliance/nis2`
- :doc:`/evidence-library/control-to-proof`

---

Key Takeaway
------------

NIS2 compliance is not achieved through documentation.

It is achieved through **engineering discipline,
operational clarity, and continuous evidence**.
