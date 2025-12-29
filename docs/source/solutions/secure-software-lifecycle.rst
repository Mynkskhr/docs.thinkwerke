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
- Software Composition Analysis (S


