Solutions & Architectures
=========================

This section documents **how security, compliance, and resilience are
implemented in practice** across cloud platforms, software delivery pipelines,
and operating models.

The focus is on **execution**, not abstract frameworks.


Purpose of this section
-----------------------

The Solutions & Architectures section exists to answer a single question:

**How do regulated organisations actually implement security and compliance
controls in modern, vendor-hosted environments?**

It covers:

- Secure software delivery patterns
- Vulnerability and supply-chain governance
- Cloud security foundations and shared responsibility
- Detection, response, and monitoring architectures
- Container and Kubernetes security models


What these solutions are designed to achieve
---------------------------------------------

All architectures documented here aim to:

- Translate regulatory and customer requirements into **technical controls**
- Produce **continuous, audit-ready evidence**
- Support engineering speed rather than slow it down
- Create defensible positions for audits, tenders, and customer reviews
- Clarify ownership in vendor-hosted and shared-responsibility environments


How to use this section
-----------------------

Use these documents as:

- **Reference architectures** when designing or reviewing systems
- **Implementation guidance** for engineering and platform teams
- **Assurance support** during audits, tenders, and customer assessments
- **Alignment material** between security, compliance, and engineering teams

Each solution page is self-contained and can be read independently.


Scope and assumptions
---------------------

Unless stated otherwise, the solutions documented here assume:

- Cloud-hosted or vendor-managed infrastructure (e.g. AWS, managed services)
- CI/CD-driven software delivery
- Multiple teams contributing to a shared product or platform
- Regulatory or customer-driven security requirements

These solutions are **tool-agnostic by design**.
Specific technologies are referenced only to illustrate implementation
patterns, not to mandate products.


Relationship to Compliance Mapping
----------------------------------

This section focuses on **how controls are built**.

The **Compliance Mapping** section focuses on **why those controls exist**
and how they align with:

- ISO/IEC 27001
- NIS2
- Cyber Resilience Act (CRA)
- GDPR
- Customer security requirements

Together, they form a complete chain:

**Requirement → Control → Implementation → Evidence**


Solution areas covered
----------------------

The following solution domains are documented in detail:

- Secure Software Lifecycle (SSLM)
- Vulnerability Lifecycle & Supply-Chain Governance
- Cloud Security Foundations
- SOC & SIEM Modernisation
- CNAPP and Kubernetes Security Architecture


What this section does not replace
----------------------------------

These documents do not replace:

- Formal policies or ISMS documentation
- Legal interpretations of regulations
- Vendor security documentation
- Auditor judgment

They exist to ensure that **what is documented can be implemented and proven**.


Next steps
----------

Start with the solution most relevant to your current challenge:

- If delivery speed and compliance are in tension → Secure Software Lifecycle
- If audits or tenders are blocked → Vulnerability Lifecycle or Evidence Library
- If ownership is unclear in the cloud → Cloud Security Foundations
- If detection and response are immature → SOC & SIEM Modernisation
- If containers and Kubernetes are in scope → CNAPP & Kubernetes Architecture


