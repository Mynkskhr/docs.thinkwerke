SOC & SIEM Modernisation
========================

Purpose
-------

This document describes how Thinkwerke approaches **Security Operations Centre (SOC) and SIEM modernisation**
for cloud-native and regulated environments.

The focus is not on deploying a SIEM tool, but on building an **operational security capability**
that delivers detection, response, accountability, and audit-ready evidence.

---

Why Traditional SOC Models Fail
-------------------------------

Many organisations operate a SIEM but still struggle with:

- Alert fatigue with no clear prioritisation
- Poor signal-to-noise ratio
- No defined ownership for alerts
- Manual incident handling
- Weak linkage between detections, risk, and compliance

In regulated environments, this results in:

- Inability to demonstrate detection effectiveness
- Audit findings around monitoring and incident response
- Over-reliance on external SOC providers without visibility

SOC modernisation addresses these gaps.

---

Design Principles
-----------------

Thinkwerke SOC and SIEM designs follow these principles:

- Detection engineering over log collection
- Cloud-native telemetry first
- Clear ownership and escalation paths
- Automation wherever possible
- Evidence generation as part of normal operations

---

Core Components
---------------

### 1. Telemetry Architecture

Effective detection starts with reliable data.

Telemetry sources typically include:

- Cloud control-plane logs
- Identity and access activity
- Network flow and DNS data
- Application and platform logs
- CI/CD and deployment events

Logs are centralised, normalised, and retained according to regulatory requirements.

---

### 2. Detection Engineering

Detections are engineered, not auto-generated.

This includes:

- Use-case driven detection design
- Mapping detections to MITRE ATT&CK
- Risk-based prioritisation
- Clear expected outcomes per detection

Each detection answers:

- What threat or failure is being detected?
- Why does it matter?
- Who owns the response?

---

### 3. Alert Triage and Ownership

Alerts without ownership create risk.

Modern SOC design defines:

- Triage responsibilities
- Severity classification
- Escalation paths
- Decision authority

Every alert has a **named owner**, whether in security, platform, or engineering teams.

---

### 4. Incident Response Integration

SIEM is tightly integrated with incident response workflows.

This includes:

- Automated case creation
- Defined response playbooks
- Evidence capture during response
- Post-incident review and improvement

Incident handling supports both operational recovery and regulatory reporting.

---

### 5. Metrics, Reporting, and Dashboards

SOC effectiveness must be visible to leadership.

Dashboards typically cover:

- Detection coverage
- Alert volume and trends
- Mean time to detect (MTTD)
- Mean time to respond (MTTR)
- Open risk and unresolved findings

Reporting is tailored for:

- Engineering teams
- Security leadership
- Executives
- Auditors and regulators

---

Operating Model
---------------

SOC modernisation includes a clear operating model defining:

- Roles and responsibilities
- Shift coverage or on-call models
- Internal vs external SOC boundaries
- Handover and escalation rules

This removes ambiguity during incidents and audits.

---

Evidence and Audit Readiness
----------------------------

SOC operations generate continuous evidence, including:

- Logged detection events
- Alert handling records
- Incident timelines
- Response approvals and outcomes

This evidence supports:

- ISO 27001 monitoring and incident controls
- NIS2 detection and response obligations
- Customer security assessments
- Regulatory reporting requirements

---

Relationship to Other Solutions
-------------------------------

SOC and SIEM modernisation depends on and supports:

- :doc:`cloud-security-foundations`
- :doc:`vulnerability-lifecycle`
- :doc:`cnapp-kubernetes`

A SOC without strong foundations becomes reactive and fragile.

---

Compliance Mapping
------------------

This solution supports:

- **ISO/IEC 27001**
  - A.5.25 Logging and monitoring
  - A.5.28 Incident management
- **NIS2**
  - Detection, response, and reporting obligations
- **CRA**
  - Operational monitoring and vulnerability handling

---

Key Takeaway
------------

A modern SOC is not a tool or a team.
It is an **operational capability** that connects telemetry, detection,
response, governance, and evidence into a single, defensible system.


