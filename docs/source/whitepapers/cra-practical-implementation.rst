Cyber Resilience Act (CRA): Practical Implementation Guide
==========================================================

From Legal Obligation to Engineering Reality
--------------------------------------------

Purpose
-------

This whitepaper explains how the **EU Cyber Resilience Act (CRA)**
translates into **practical engineering, delivery, and operating model changes**
for organisations developing, delivering, or operating digital products.

It focuses on **how CRA requirements are implemented**, not how they are interpreted legally.

---

What the CRA Introduces
-----------------------

The Cyber Resilience Act establishes **mandatory cybersecurity requirements**
for products with digital elements placed on the EU market.

Key shifts introduced by the CRA include:

- Security obligations across the **entire product lifecycle**
- Explicit responsibility for **software vulnerabilities**
- Mandatory handling of **known exploited vulnerabilities**
- Strong emphasis on **software supply-chain transparency**
- Enforcement through market surveillance and penalties

CRA applies not only to vendors, but also to organisations
that **design, integrate, customise, or operate software products**.

---

Engineering Impact of the CRA
-----------------------------

CRA fundamentally changes how software must be built and maintained.

From an engineering perspective, CRA requires:

- Secure-by-design development practices
- Continuous vulnerability management
- Traceability from code to deployed product
- Evidence that security controls are active and effective

CRA cannot be satisfied through documentation alone.
It must be **implemented in pipelines, workflows, and platforms**.

---

Core Engineering Domains
------------------------

### Secure Software Lifecycle (SSLM)

CRA mandates security across:

- Design
- Development
- Build
- Deployment
- Maintenance
- End-of-life

This requires:

- Secure CI/CD pipelines
- Automated security testing
- Policy enforcement in delivery workflows
- Clear ownership of remediation actions

---

### Vulnerability Management

CRA places strong emphasis on vulnerability handling.

Practical requirements include:

- Identification of vulnerabilities (including OSS)
- Prioritisation based on risk and exploitability
- Defined remediation timelines
- Traceable remediation evidence

Engineering teams must implement:

- Detection → triage → remediation → verification workflows
- SLA-based handling
- Audit-ready records

---

### Software Supply-Chain Governance

CRA requires transparency into software components.

This includes:

- Software Bill of Materials (SBOM)
- Open-source license governance
- Dependency risk assessment
- Third-party component accountability

SBOMs are not sufficient on their own.
They must be integrated into:

- CI/CD pipelines
- Vulnerability tooling
- Evidence repositories

---

### Product & Platform Security

CRA applies to the **product**, not just the source code.

This means:

- Secure configuration of runtime environments
- Platform hardening
- Identity and access controls
- Logging and monitoring

For cloud-native products, CRA requires
clear linkage between **product responsibilities** and **platform controls**.

---

Evidence Expectations Under CRA
-------------------------------

CRA enforcement relies on the ability to demonstrate:

- Security measures are implemented
- Vulnerabilities are handled correctly
- Products are maintained securely over time

Typical evidence includes:

- CI/CD security scan results
- SBOM artefacts
- Vulnerability remediation records
- Change and release approvals
- Security advisories and notifications

Evidence must be:

- Continuous
- Tamper-resistant
- Traceable to product versions

---

Vendor-Hosted & Shared Responsibility
-------------------------------------

Many CRA-scoped products run on:

- Public cloud
- Managed Kubernetes
- Third-party platforms

CRA does not allow responsibility to be shifted entirely to vendors.

Organisations must show:

- Which security responsibilities are owned internally
- Which are inherited from vendors
- How inherited controls are validated
- How gaps are mitigated

This requires explicit **responsibility mapping** and **defensible narratives**.

---

Common Implementation Pitfalls
-------------------------------

CRA implementations often fail when:

- SBOMs are generated but not maintained
- Vulnerability handling lacks ownership
- Security checks are bypassable
- Evidence is manually assembled
- Product teams are disconnected from compliance teams

These failures increase regulatory and commercial risk.

---

A Practical Implementation Model
--------------------------------

A defensible CRA implementation typically includes:

1. CRA requirement mapping to engineering controls
2. Secure-by-design CI/CD pipelines
3. Integrated SBOM and vulnerability workflows
4. Product-centric evidence generation
5. Clear ownership across product, platform, and security teams

---

Relationship to Other Materials
-------------------------------

This whitepaper is supported by:

- :doc:`/solutions/secure-software-lifecycle`
- :doc:`/solutions/vulnerability-lifecycle`
- :doc:`/solutions/cnapp-kubernetes`
- :doc:`/compliance/cra`
- :doc:`/evidence-library/control-to-proof`

---

Key Takeaway
------------

The Cyber Resilience Act is not a documentation exercise.

It is a **product engineering obligation** that demands
secure delivery pipelines, disciplined vulnerability management,
and continuous evidence across the product lifecycle.


