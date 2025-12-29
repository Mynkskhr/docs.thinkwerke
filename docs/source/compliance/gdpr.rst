GDPR: Privacy Engineering & Data Protection by Design
======================================================

Purpose
-------

This document explains how Thinkwerke approaches **GDPR**
as a **privacy engineering and system design discipline**,
not a policy or legal-only exercise.

The focus is on implementing **data protection by design and by default**
through architecture, engineering workflows, and continuous evidence.

---

What GDPR Actually Requires
---------------------------

GDPR requires organisations to:

- Protect personal data throughout its lifecycle
- Minimise data collection and processing
- Control access and usage
- Detect, respond to, and report incidents
- Demonstrate compliance at any time

These requirements directly affect **system architecture,
software design, and operations**.

---

Common GDPR Failure Patterns
----------------------------

GDPR implementations often fail because:

- Privacy is handled only in policies
- Data flows are undocumented or outdated
- Engineering teams lack privacy design guidance
- DPIAs are static documents with no technical linkage
- Evidence cannot be produced consistently

Thinkwerke addresses these gaps through privacy-by-design engineering.

---

Thinkwerke Privacy Engineering Model
------------------------------------

GDPR is implemented across four layers:

1. Data flow transparency
2. Privacy threat modeling
3. Technical and organisational controls
4. Continuous evidence and monitoring

Each layer is tied to real systems and workflows.

---

LINDDUN Privacy Threat Modeling
-------------------------------

Thinkwerke uses **LINDDUN** as a structured method
to identify and mitigate privacy risks early in design.

LINDDUN focuses on the following threat categories:

- **Linkability**
- **Identifiability**
- **Non-repudiation**
- **Detectability**
- **Information disclosure**
- **Unawareness**
- **Non-compliance**

These threats are mapped to system components,
data flows, and processing activities.

---

Applying LINDDUN in Practice
----------------------------

LINDDUN is applied during:

- Architecture design
- New feature development
- Cloud platform changes
- Vendor and service integration

Outputs include:

- Identified privacy risks
- Design mitigations
- Control ownership
- Traceable links to GDPR requirements

This prevents late-stage privacy blockers.

---

Data Flow Mapping
-----------------

GDPR compliance starts with accurate data flow visibility:

- What personal data is processed
- Where it is stored
- How it moves between systems
- Who can access it
- How long it is retained

Data flows are kept current and tied to implementations.

---

Technical Control Implementation
--------------------------------

GDPR controls are implemented through:

- Identity and access management
- Encryption at rest and in transit
- Logging and access monitoring
- Data minimisation in applications
- Secure deletion and retention enforcement

Controls are enforced through configuration and code.

---

DPIA as a Living Artefact
------------------------

Data Protection Impact Assessments (DPIAs) are treated as:

- Living design artefacts
- Linked to architecture and data flows
- Updated as systems evolve
- Supported by technical evidence

This aligns DPIAs with real system behavior.

---

Incident Detection and Breach Response
--------------------------------------

GDPR breach response is enabled through:

- Centralised logging and monitoring
- Clear incident classification criteria
- Response workflows and timelines
- Evidence-backed reporting decisions

This supports regulatory notification requirements.

---

Evidence and Audit Readiness
----------------------------

GDPR evidence is generated continuously via:

- Access logs and reviews
- Configuration states
- DPIA updates
- Privacy risk assessments
- Incident handling records

This enables rapid response to regulator inquiries.

---

Relationship to Other Frameworks
--------------------------------

GDPR privacy engineering integrates with:

- ISO/IEC 27001 technical controls
- NIS2 operational monitoring
- CRA secure product expectations

See also:

- :doc:`iso27001`
- :doc:`nis2`
- :doc:`cra`
- :doc:`crosswalks`

---

Key Takeaway
------------

GDPR compliance succeeds when privacy is **designed into systems**,
not documented around them.

By applying LINDDUN-based threat modeling,
data protection becomes measurable, enforceable,
and defensible across cloud and product architectures.

