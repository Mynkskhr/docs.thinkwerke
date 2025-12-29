CNAPP & Kubernetes Security Architecture
========================================

Purpose
-------

This document explains how Thinkwerke approaches **CNAPP and Kubernetes security**
for regulated and cloud-native environments.

The goal is not to deploy another security platform,
but to establish **clear accountability, enforceable controls, and audit-ready evidence**
across cloud infrastructure, containers, and Kubernetes workloads.

---

Why Kubernetes Changes the Security Model
------------------------------------------

Kubernetes introduces a shared responsibility model across:

- Cloud provider
- Platform teams
- Application teams
- CI/CD pipelines

Common failures include:

- Unclear ownership of cluster security
- Runtime visibility without enforcement
- Tool overlap without governance
- Inability to prove controls to auditors

CNAPP must be **architected**, not just enabled.

---

Design Principles
-----------------

Thinkwerke CNAPP and Kubernetes designs follow these principles:

- Accountability before tooling
- Policy enforcement close to deployment
- Runtime visibility with response ownership
- Evidence generation as part of normal operations
- Minimal friction for engineering teams

---

What CNAPP Covers (Practically)
-------------------------------

In Thinkwerke implementations, CNAPP spans:

- Cloud Security Posture Management (CSPM)
- Infrastructure-as-Code security
- Container image security
- Kubernetes configuration security
- Runtime threat detection

Each capability is mapped to a **control owner** and **response workflow**.

---

Kubernetes Security Architecture
--------------------------------

### 1. Cluster Foundations

Secure clusters start with strong foundations:

- Managed Kubernetes with hardened configurations
- Network segmentation and policy enforcement
- Secure API server access
- Centralised logging and monitoring

Foundations are designed once and reused across environments.

---

### 2. Workload Security

Workload security focuses on:

- Image provenance and integrity
- Approved base images
- Admission controls
- Least-privilege runtime permissions

Controls are enforced **before deployment**, not after compromise.

---

### 3. Runtime Visibility and Response

Runtime security is treated as an operational capability:

- Behavioural detection
- Anomaly identification
- Integration with SOC and incident workflows
- Automated or guided response actions

Runtime alerts without ownership are explicitly avoided.

---

### 4. Policy-as-Code

Security policies are implemented as code:

- Kubernetes admission policies
- Infrastructure policies
- CI/CD enforcement rules

This enables:

- Consistent enforcement
- Version control
- Traceability
- Auditability

---

Operating Model
---------------

CNAPP success depends on an operating model defining:

- Platform team responsibilities
- Application team obligations
- Security oversight
- Exception handling and approvals

This prevents security from becoming either invisible or obstructive.

---

Evidence and Audit Readiness
----------------------------

Kubernetes and CNAPP controls continuously generate evidence:

- Policy enforcement logs
- Admission decisions
- Deployment approvals
- Runtime event handling

This evidence supports:

- ISO 27001 technical control validation
- NIS2 operational monitoring
- CRA product security expectations
- Customer and regulator reviews

---

Relationship to Other Solutions
-------------------------------

CNAPP and Kubernetes security integrate with:

- :doc:`cloud-security-foundations`
- :doc:`secure-software-lifecycle`
- :doc:`soc-siem-modernisation`

Without these, CNAPP becomes an isolated tool rather than a capability.

---

Compliance Mapping
------------------

This solution supports:

- **ISO/IEC 27001**
  - A.5.15 Access control
  - A.5.23 Information security for use of cloud services
- **NIS2**
  - Risk management and operational resilience
- **CRA**
  - Secure deployment and operational controls

---

Key Takeaway
------------

Kubernetes security is not about controlling containers.
It is about **controlling responsibility, enforcement, and evidence**
across a dynamic cloud platform.

CNAPP works only when it is aligned with architecture, operations, and governance.


