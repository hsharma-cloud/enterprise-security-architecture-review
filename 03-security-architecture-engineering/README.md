# Security Architecture & Engineering

Security Architecture & Engineering focuses on designing, implementing, and maintaining secure systems that support organizational objectives while managing risk. It establishes the principles, models, technologies, and engineering practices that form the foundation of enterprise security.

This domain encompasses secure design principles, security models, cryptography, system security capabilities, architecture risk assessment, physical security, and system lifecycle management.

---

# Why This Domain Matters

Security architecture provides the blueprint for protecting organizational assets.

Effective security architecture ensures that security controls are integrated into systems by design rather than added after deployment. Engineering practices translate security requirements into technical implementations that support confidentiality, integrity, availability, resilience, and trust.

Organizations rely on security architecture to establish consistent, scalable, and defensible security solutions across infrastructure, applications, cloud environments, and operational technologies.

---

# Architecture Perspective

Security architecture begins with business and security requirements and translates them into technical controls and system designs.

```text
Business Requirements
          ↓
Security Requirements
          ↓
Architecture Design
          ↓
Security Controls
          ↓
Implementation
          ↓
Validation
          ↓
Operations
```

---

# Domain Coverage

This domain includes the following major areas:

## Secure Design Principles

* Least Privilege
* Defense in Depth
* Secure Defaults
* Fail Securely
* Segregation of Duties
* Privacy by Design
* Shared Responsibility
* Zero Trust Architecture

---

## Security Models

* Bell-LaPadula
* Biba
* Star Model
* Information Flow Models
* Access Control Models

---

## Security Control Selection

* Technical controls
* Administrative controls
* Physical controls
* Control alignment with security requirements

---

## System Security Capabilities

* Memory Protection
* Trusted Platform Module (TPM)
* Secure Boot
* Encryption
* Virtualization Security

---

## Architecture Risk Assessment

* Client Systems
* Server Systems
* Database Systems
* Distributed Systems
* Cloud Systems
* Virtualized Environments

---

## Modern Technology Architectures

* Cloud Computing
* Containers
* Microservices
* APIs
* Serverless Computing
* Edge Computing
* Internet of Things (IoT)

---

## Cryptography & Key Management

* Symmetric Encryption
* Asymmetric Encryption
* Elliptic Curve Cryptography
* Public Key Infrastructure (PKI)
* Key Lifecycle Management
* Digital Certificates
* Digital Signatures

---

## Cryptographic Attacks

* Brute Force
* Known Plaintext
* Ciphertext Only
* Frequency Analysis
* Side-Channel Attacks
* Man-in-the-Middle (MITM)

---

## Physical Security Architecture

* Site Selection
* Environmental Controls
* Physical Barriers
* Facility Security Design

---

## Facility Security Controls

* Data Centers
* Server Rooms
* Media Storage
* Evidence Storage
* Power Systems
* Fire Suppression Systems
* HVAC Controls

---

## System Lifecycle Security

* Requirements Analysis
* Architecture Design
* Development
* Testing
* Deployment
* Operations
* Retirement

---

# Security Decision Patterns

## Architecture vs Implementation

Architecture:

Defines the design and structure.

Implementation:

Builds the solution.

---

## Symmetric vs Asymmetric Encryption

Symmetric:

Uses a shared secret key.

Asymmetric:

Uses a public and private key pair.

---

## Defense in Depth vs Single Control

Defense in Depth:

Multiple layers of protection.

Single Control:

One point of failure.

---

## Secure by Design vs Secure by Configuration

Secure by Design:

Security integrated during design.

Secure by Configuration:

Security added after deployment.

---

## PKI vs Digital Signature

PKI:

Establishes trust relationships.

Digital Signature:

Provides integrity, authenticity, and nonrepudiation.

---

# Related Security Architecture Patterns

This domain directly supports:

* Defense in Depth
* Zero Trust Architecture
* Public Key Infrastructure
* Shared Responsibility Model
* Secure Development Lifecycle
* Network Segmentation

Refer to:

`references/security-architecture-patterns.md`

for related architecture patterns.

---

# Key Takeaways

* Security architecture provides the foundation for enterprise security.
* Security controls should be integrated by design.
* Secure design principles guide engineering decisions.
* Cryptography enables confidentiality, integrity, authenticity, and trust.
* Modern architectures introduce new security considerations.
* Physical and logical security must work together.
* Security must be maintained throughout the system lifecycle.

---

# Related Domains

This domain has strong relationships with:

* Governance, Risk & Compliance
* Network & Infrastructure Security
* Identity & Access Security
* Security Operations & Resilience
* Secure Application & Software Security

Security architecture serves as the bridge between business requirements and technical implementation across the enterprise.
