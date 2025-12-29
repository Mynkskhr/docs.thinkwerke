Secure Software Lifecycle (SSLM)
================================

This document describes how a **secure software lifecycle** is implemented
in regulated, vendor-hosted environments in a way that produces
**continuous, auditable evidence** without slowing delivery.

The focus is on **practical execution**, ownership, and traceability.


Why SSLM matters in regulated environments
-------------------------------------------

Modern regulations and customer security requirements increasingly expect
organisations to demonstrate:

- Secure development practices
- Control over third-party and open-source components
- Continuous vulnerability management
- Evidence that security controls are applied consistently

SSLM provides the **technical foundation** for meeting these expectations
across ISO 27001, NIS2, and the Cyber Resilience Act (CRA).


Core principles
---------------

A compliant SSLM implementation follows these principles:

- **Shift left, but verify continuously**
- **Automate wherever possible**
- **Separate policy from enforcement**
- **Make evidence a by-product of delivery**
- **Keep ownership with engineering teams**


Lifecycle stages
----------------

The secure software lifecycle is implemented across the following stages.


1. Design & planning
~~~~~~~~~~~~~~~~~~~~

Security begins before code is written.

Key practices include:

- Threat modelling aligned to product context
- Architecture decisions documented and versioned
- Security requirements linked to backlog items
- Clear definition of control ownership

Outputs:

- Architecture decision records (ADRs)
- Threat models
- Security requirements mapped to features


2. Build & dependency management
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

During development and build:

- Source code is continuously scanned
- Open-source dependencies are inventoried
- Licensing constraints are evaluated

Typical controls:

- Static Application Security Testing (SAST)
- Software Composition Analysis (SCA)
- Automated SBOM generation

Outputs:

- Scan results linked to commits
- SBOM artefacts per build
- Dependency and license reports


3. Pipeline enforcement
~~~~~~~~~~~~~~~~~~~~~~~

CI/CD pipelines enforce security controls consistently.

Controls typically include:

- Policy-as-code gates
- Minimum security baselines
- Environment separation (build, test, production)

Pipelines are designed so that:

- Failures are actionable
- Exceptions are traceable
- Overrides require approval

Outputs:

- Pipeline execution logs
- Policy evaluation results
- Approval records


4. Testing & verification
~~~~~~~~~~~~~~~~~~~~~~~~~

Beyond static checks, runtime and configuration issues are validated.

Common practices:

- Dynamic Application Security Testing (DAST)
- Infrastructure-as-Code (IaC) scanning
- Container image scanning

Outputs:

- Test results tied to pipeline runs
- Identified issues with severity and context
- Evidence of remediation or risk acceptance


5. Release & deployment
~~~~~~~~~~~~~~~~~~~~~~~

Before release:

- Artefact integrity is verified
- Provenance is established
- Release approvals are recorded

Typical mechanisms:

- Artifact signing
- Attestation of build provenance
- Environment-specific deployment approvals

Outputs:

- Signed artefacts
- Deployment records
- Release approval evidence


6. Operate & maintain
~~~~~~~~~~~~~~~~~~~~~

After deployment, security continues.

Practices include:

- Continuous vulnerability monitoring
- Patch and remediation workflows
- Change tracking for deployed systems

Outputs:

- Vulnerability lifecycle records
- Change management evidence
- Monitoring and alerting data


Evidence-by-design
------------------

A key objective of SSLM is that **evidence is generated automatically**.

Rather than preparing evidence manually for audits or tenders, SSLM produces:

- Timestamped artefacts
- Immutable logs
- Traceability across requirements, code, and deployment

This enables:

- Faster audits
- Predictable tender responses
- Reduced engineering disruption


Alignment with regulations
--------------------------

SSLM directly supports:

- ISO/IEC 27001 (A.8, A.12, A.14, A.18)
- NIS2 risk management and supply-chain controls
- CRA secure development and vulnerability handling requirements
- Customer security questionnaires and assurance requests

Detailed mappings are covered in the Compliance Mapping section.


What SSLM does not solve alone
------------------------------

SSLM is necessary, but not sufficient on its own.

It must be complemented by:

- Cloud security foundations
- Clear vulnerability ownership models
- SOC and incident response capabilities
- Governance and reporting structures

These are covered in adjacent solution documents.


Next steps
----------

To continue, review:

- **Vulnerability Lifecycle** for how issues are handled end-to-end
- **Cloud Security Foundations** for infrastructure-level controls
- **Evidence Library** for how SSLM outputs are reused in audits and tenders
