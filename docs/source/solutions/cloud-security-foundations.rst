Cloud Security Foundations
==========================

Purpose
-------

This document describes the **baseline cloud security foundations** required to operate
secure, compliant, and resilient workloads in public cloud environments.

The focus is on **repeatable architecture and governance**, not individual security tools.
These foundations form the control layer upon which Secure Software Lifecycle (SSLM),
vulnerability management, CNAPP, and SOC operations depend.

The reference implementation assumes **AWS**, but the principles are cloud-agnostic.

---

Why Cloud Security Foundations Matter
-------------------------------------

Many organisations adopt cloud services faster than they establish governance.
Common symptoms include:

- Inconsistent account structures
- Weak identity boundaries
- Fragmented logging and monitoring
- Manual security reviews
- Unclear shared-responsibility ownership

For regulated organisations, these gaps translate directly into **audit findings,
customer assurance failures, and operational risk**.

Cloud security foundations exist to make security **predictable, observable, and provable**.

---

Design Principles
-----------------

Thinkwerke foundations are built around the following principles:

- Security by default, not by exception
- Centralised visibility with decentralised ownership
- Automation over manual review
- Clear separation of duties
- Evidence generation as a first-class requirement

---

Core Foundation Components
--------------------------

### 1. Account and Environment Structure

A structured multi-account model is used to separate:

- Production and non-production workloads
- Shared services (logging, security tooling)
- Management and governance functions

Benefits:

- Reduced blast radius
- Clear ownership boundaries
- Stronger auditability

---

### 2. Identity and Access Management (IAM)

Identity is treated as the primary security control.

Key elements include:

- Centralised identity provider integration
- Role-based access with least privilege
- No long-lived credentials
- Strong separation between human and machine identities

Access decisions are **traceable and reviewable**, supporting ISO 27001 and NIS2 requirements.

---

### 3. Network Security Baseline

The network layer provides controlled connectivity without becoming a bottleneck.

Typical controls include:

- Segmented VPC design
- Restricted ingress and egress paths
- Private service access where possible
- Explicit trust boundaries between services

Network design is documented and mapped to control objectives.

---

### 4. Logging and Monitoring Foundations

All security and operational decisions depend on **reliable telemetry**.

Foundational logging includes:

- Cloud API activity
- Identity and access events
- Network flows
- Platform and service logs

Logs are:

- Centralised
- Immutable
- Retained according to regulatory requirements

This layer enables SOC, SIEM, and incident response workflows.

---

### 5. Posture Management (CSPM)

Cloud Security Posture Management provides continuous visibility into:

- Configuration drift
- Policy violations
- Exposure risks
- Control coverage

Posture findings are integrated into the broader vulnerability and governance lifecycle,
not handled in isolation.

---

### 6. Secure CI/CD Integration

Cloud foundations extend into delivery pipelines.

This includes:

- Secure identity for pipelines
- Controlled deployment permissions
- Infrastructure-as-Code validation
- Traceable change history

Every deployment becomes **auditable by design**.

---

Operating Model
---------------

Security foundations are effective only when paired with an operating model.

Key responsibilities include:

- Platform ownership (cloud teams)
- Control ownership (security and compliance)
- Application ownership (engineering teams)
- Oversight and assurance (GRC or risk functions)

Roles are explicitly defined to avoid ambiguity during incidents or audits.

---

Evidence and Audit Readiness
----------------------------

Foundations are designed to generate continuous evidence, including:

- Identity and access records
- Configuration baselines
- Logging coverage
- Change and deployment history

This evidence supports:

- ISO 27001 certification and surveillance audits
- NIS2 compliance demonstrations
- CRA technical documentation
- Customer security assessments

---

Relationship to Other Solutions
-------------------------------

Cloud security foundations enable and support:

- :doc:`secure-software-lifecycle`
- :doc:`vulnerability-lifecycle`
- :doc:`cnapp-kubernetes`
- :doc:`soc-siem-modernisation`

Without strong foundations, higher-level security controls become fragile.

---

Compliance Mapping
------------------

This solution supports:

- **ISO/IEC 27001**
  - A.5.15 Identity management
  - A.8.15 Logging
  - A.8.23 Network security
- **NIS2**
  - Risk management measures
  - Incident detection and response readiness
- **CRA**
  - Secure-by-design infrastructure
  - Operational resilience requirements

---

Key Takeaway
------------

Cloud security foundations are not a one-time setup.
They are a **living control layer** that enables speed, resilience, and trust
across the entire software and cloud lifecycle.


