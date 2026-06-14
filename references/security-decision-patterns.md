# Security Decision Separators

This document captures key concept distinctions, decision frameworks, and discriminator patterns used across enterprise security domains.

Understanding these distinctions helps prevent confusion between similar concepts and improves security decision-making.

---

# Domain 1 – Governance, Risk & Compliance

## Due Care vs Due Diligence

Due Care:
Doing the right thing.

Due Diligence:
Proving the right thing was done.

---

## Risk Mitigation vs Risk Avoidance

Risk Mitigation:
Reduce risk.

Risk Avoidance:
Eliminate the activity causing risk.

---

## Governance vs Management

Governance:
Strategic direction.

Management:
Operational execution.

---

## Policy vs Standard

Policy:
High-level requirement.

Standard:
Mandatory implementation requirement.

---

## Procedure vs Guideline

Procedure:
Required process.

Guideline:
Recommended approach.

---

# Domain 4 – Network & Infrastructure Security

## North-South vs East-West Traffic

North-South:
Traffic entering or leaving a network.

East-West:
Traffic moving within a network.

---

## IDS vs IPS

IDS:
Detects.

IPS:
Detects and blocks.

---

## VPN vs TLS

VPN:
Network-level protection.

TLS:
Session/Application-level protection.

---

## Physical vs Logical Segmentation

Physical:
Separate hardware.

Logical:
Segmentation through configuration.

---

## Router vs Firewall

Router:
Routes traffic.

Firewall:
Enforces security policy.

---

# Domain 5 – Identity & Access Security

## Identification vs Authentication

Identification:
Claiming an identity.

Authentication:
Proving an identity.

---

## Authentication vs Authorization

Authentication:
Who are you?

Authorization:
What are you allowed to do?

---

## Authorization vs Accountability

Authorization:
Permissions.

Accountability:
Auditability.

---

## RBAC vs ABAC

RBAC:
Access based on role.

ABAC:
Access based on attributes.

---

## Federation vs Single Sign-On

Federation:
Trust relationship.

Single Sign-On:
User experience.

---

## Identity Proofing vs Authentication

Identity Proofing:
Establish identity.

Authentication:
Verify identity.

---

# Domain 7 – Security Operations & Resilience

## Detection vs Containment

Detection:
Identify the incident.

Containment:
Limit damage.

---

## Containment vs Eradication

Containment:
Stop spread.

Eradication:
Remove root cause.

---

## Recovery vs Restoration

Recovery:
Return service.

Restoration:
Return to normal operations.

---

## Backup vs High Availability

Backup:
Recovery capability.

High Availability:
Availability capability.

---

## Business Continuity vs Disaster Recovery

Business Continuity:
Keep business operating.

Disaster Recovery:
Restore systems and technology.

---

## Evidence Preservation vs Remediation

Preserve evidence before remediation whenever investigations are required.

---

# Universal Security Principles

## Least Privilege vs Need-to-Know

Least Privilege:
Minimum permissions.

Need-to-Know:
Minimum information access.

---

## Preventive vs Detective Controls

Preventive:
Stop an event.

Detective:
Identify an event.

---

## Detective vs Corrective Controls

Detective:
Identify.

Corrective:
Fix.

---

## Confidentiality vs Integrity vs Availability

Confidentiality:
Prevent unauthorized disclosure.

Integrity:
Prevent unauthorized modification.

Availability:
Ensure access when needed.
