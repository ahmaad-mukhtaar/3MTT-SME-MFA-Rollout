# 3MTT SME MFA Rollout

## Enterprise MFA Rollout & Authentication Governance Framework

**3MTT Cybersecurity Capstone Project**

**Candidate:** Ahmad Mukhtar  
**Track:** Cybersecurity  
**Institution:** Kano State Polytechnic  
**Focus Area:** Identity & Access Management (IAM)

---

## Project Overview

This capstone presents an Enterprise Multi-Factor Authentication (MFA) Rollout and Authentication Governance Framework designed for a Small and Medium-sized Enterprise (SME).

The project addresses the security risks associated with password-only authentication, including credential compromise, brute-force attacks, phishing, and credential stuffing.

The proposed framework combines stronger password governance, mandatory MFA, phased implementation, and technical authentication verification.

---

## Problem Statement

Password-only authentication creates a significant security risk because compromised credentials can provide unauthorised access to organisational resources.

SMEs require practical security controls that strengthen authentication without creating unnecessary operational disruption.

This project therefore proposes a structured MFA governance and implementation framework that can be introduced progressively across an SME environment.

---

## Project Objectives

- Establish stronger password and passphrase governance.
- Define mandatory MFA requirements for organisational access.
- Develop a phased MFA implementation strategy.
- Validate MFA authentication behaviour in a simulated laboratory environment.
- Provide practical security and governance recommendations for SMEs.

---

## Security Policy Framework

### Password & Passphrase Governance

The proposed policy establishes:

- Minimum 14-character passwords for standard staff.
- Minimum 16-character passwords for administrative roles.
- Strong password complexity requirements.
- Use of secure random-word passphrases.
- Account suspension after repeated failed authentication attempts.
- Prohibition of common, organisational, and compromised passwords.

### Mandatory MFA Governance

MFA is proposed as mandatory for:

- Internal staff
- Contractors
- Third-party vendors accessing organisational resources
- Privileged and administrative accounts

Preferred second factors include:

- TOTP authenticator applications
- Hardware security tokens

SMS-based OTP is proposed for phase-out because of risks including SIM swapping and interception.

---

## MFA Implementation Strategy

| Phase | Timeline | Target Group |
|---|---|---|
| Phase 1 | Week 1 | IT & Global Administrators |
| Phase 2 | Week 2 | 15% Pilot Group |
| Phase 3 | Weeks 3–4 | Company-wide Deployment |

### Phase 1 — Administrator Deployment

Configure Identity Provider policies and enforce MFA for administrators before wider deployment.

### Phase 2 — Pilot Deployment

Deploy MFA to a representative 15% pilot group across selected organisational departments and gather feedback.

### Phase 3 — Company-wide Enforcement

Extend MFA enforcement across the organisation following successful pilot validation.

---

## Technical Validation

The project includes a simulated authentication validation using an Identity Provider environment and TOTP-based MFA.

The documented test demonstrates:

1. Primary credentials are supplied without the required TOTP.
2. Authentication is denied and an MFA challenge is presented.
3. The authenticator is enrolled using a QR code.
4. A valid six-digit TOTP is supplied.
5. Authentication is successfully completed.

This demonstrates the core security principle that possession of the primary password alone is insufficient when MFA enforcement is active.

---

## Security Recommendations

The project recommends:

- Enforcing MFA for organisational and privileged accounts.
- Using TOTP applications or hardware security tokens.
- Strengthening password and passphrase requirements.
- Preventing the use of compromised passwords.
- Implementing MFA through a phased rollout.
- Providing user onboarding and technical support.
- Establishing a secure account recovery process.
- Monitoring authentication and access activity.

---

## Project Deliverables

- Final MFA Capstone Assessment Report
- Authentication Governance Framework
- MFA Rollout Strategy
- Technical Validation Evidence
- Security Recommendations
- 2–3 Minute Demonstration Video

---

## Repository Contents
```text
3MTT-SME-MFA-Rollout/
├── README.md
├── MFA_Implementation_Evidence.md
├── 01-Primary-Login.jpg
├── 02-TOTP-Enrollment-QR.jpg
├── -MFA-Token-Verification-Start.jpg
├── MFA-Token-Verification-End.jpg
├── 05-MFA-Access-Granted.jpg
├── architecture/
│   └── MFA_Architecture_Spec.md
├── documentation/
│   └── MFA_Governance_Framework.md
└── report/
    └── 3MTT_MFA_Final_Report_Ahmad_Mukhtar.pdf
```
