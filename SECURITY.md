# Wield Labs Bug Bounty Program

## Introduction

At Wield Labs, we value the security of our products and the privacy of our users. We recognize the importance of security researchers in identifying vulnerabilities and welcome their contributions to help us maintain a secure environment. This Bug Bounty Program aims to reward researchers for responsibly disclosing vulnerabilities.

## Scope

### In-Scope

The following domains and applications are eligible for the bug bounty program:

- `*.far.quest`
- `com.wieldlabs.wallet` (iOS/Android far.quest)
- `*.wield.xyz`

### Out-of-Scope

We consider most informative-type issues to be out of scope, such as SPF issues. If most other bug bounty programs exclude it, we likely would too. To keep it brief, we’ll only enumerate the most important issues to avoid testing or reporting.

The following are out of scope for the bug bounty program:

- Third-party services and applications not controlled by Wield Labs
- Denial of Service (DoS) attacks
- Social engineering attacks against Wield Labs employees or contractors
- Physical attacks against Wield Labs offices or data centers
- Username enumeration
- Rate Limiting (Non-critical issues)
- Non-security-impacting UX issues
- Deprecated open source libraries (please create a GitHub issue instead)
- Vulnerabilities or weaknesses in third-party applications that integrate with Wield Labs
- Publicly available leaked credentials (database dumps) by themselves that are found on the internet are out of scope. If you are able to leverage our current systems to receive sensitive user information, the report will be considered.
- Low-Impact Vulnerabilities ("Bed Bounties"): Vulnerabilities that have minimal to no security impact, typically generated from automated security tools, such as those that do not pose any real risk to users or the system, are excluded from this program. Examples include non-exploitable configurations, overly theoretical findings, or issues that require unlikely conditions to be exploitable.

## Rewards

Rewards will be based on the severity of the vulnerability and its impact on our users. The final reward amount is at the discretion of Wield Labs - keep in mind we are a pre-seed startup.

## Common Vulnerability Scoring Standard (CVSS)

We use the Common Vulnerability Scoring Standard (CVSS) to assess and prioritize the severity of reported vulnerabilities. CVSS is an open framework that provides a standardized way of assessing the severity of security vulnerabilities. It takes into account various factors, such as:

- **Attack Vector**: The method by which the vulnerability is exploited (e.g., network, adjacent, local, physical).
- **Attack Complexity**: The complexity of the attack required to exploit the vulnerability.
- **Privileges Required**: The level of privileges an attacker must have to exploit the vulnerability.
- **User Interaction**: The level of user interaction required for the exploitation to be successful.
- **Confidentiality Impact**: The impact on the confidentiality of the data.
- **Integrity Impact**: The impact on the integrity of the data.
- **Availability Impact**: The impact on the availability of the affected system.

The CVSS score ranges from 0.0 to 10.0, with higher scores indicating more severe vulnerabilities. Wield Labs uses this score to help determine the priority and reward for each reported vulnerability.

## Reporting a Vulnerability

To report a vulnerability, please follow these steps:

1. **Email**: Send an email to security@wield.xyz with the subject "Bug Bounty Submission".
2. **Include**:
   - A detailed description of the vulnerability.
   - Steps to reproduce the vulnerability.
   - Potential impact and security risk.
   - Any relevant screenshots, proof-of-concept code, or other supporting materials.
3. **Wait for Confirmation**: We will acknowledge receipt of your report within 72 hours and provide feedback on the next steps.

## Disclosure Policy

- **Responsible Disclosure**: Researchers must follow responsible disclosure practices. Do not disclose the vulnerability publicly until Wield Labs has had adequate time to address it.
- **Non-Disclosure Agreement**: Researchers may be required to sign a non-disclosure agreement before receiving a reward.
- **Legal Safe Harbor**: If you identify a vulnerability in compliance with this policy, we will not pursue or support any legal action against you. However, any actions that are in violation of the law or this policy are not covered.

## Eligibility

To be eligible for a reward:

- You must be the first person to report the vulnerability.
- You must not be a current or former employee of Wield Labs or its subsidiaries.
- You must not be involved in the development, administration, or direct operation of Wield Labs systems.

## Program Rules

- **Do not** exploit any vulnerabilities beyond what is necessary to prove its existence.
- **Do not** conduct any testing that could result in the disruption of our services.
- **Do not** attempt to access, modify, or delete any data that does not belong to you.
- **Do not** use social engineering techniques against Wield Labs employees or contractors.
- **Do** follow responsible disclosure practices and maintain confidentiality of any vulnerabilities discovered.

## Contact

If you have any questions about the bug bounty program, please contact us at security@wield.xyz.

Thank you for helping us keep Wield Labs secure!

---

_Wield Labs reserves the right to modify the terms of this Bug Bounty Program at any time._
