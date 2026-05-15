# Phala Network Responsible Disclosure

At Phala Network, we take the security of our production systems seriously. If you believe you have found a security vulnerability in an in-scope Phala-operated asset, please report it to us so we can investigate and remediate it.

Submit reports by email to <cert@phala.network>. Please do not submit product bugs, feature requests, or issues without practical security impact through this program.

This Responsible Disclosure program, Bug Bounty program, scope, and listed rewards are subject to change at any time.

## In Scope

The program covers security vulnerabilities with clear, reproducible end-to-end impact against production assets operated by Phala, including:

- Phala Cloud production services.
- Active Phala-operated production web applications and APIs.
- Other production assets that Phala explicitly announces as in scope.

## Out of Scope

The following are out of scope unless Phala explicitly announces otherwise:

- Legacy Phala Blockchain, parachain, runtime, pRuntime, pherry, and runtime-bridge components that are archived, sunset, deprecated, or no longer production-operated.
- Test, staging, demo, deprecated, parked, or otherwise non-production assets, even when hosted under Phala domains.
- Third-party services, applications, or infrastructure not operated by Phala.
- Findings without a clear, reproducible end-to-end production security impact.
- Scanner-only findings, automated best-practice reports, or issues that do not include a practical exploit path.
- SPF, DKIM, DMARC, DANE, security headers, clickjacking, CORS, open directories, or weak cipher findings without practical exploitability.
- Open redirect or HTML injection findings without account compromise, sensitive-token leakage, or another demonstrated production impact.
- Rate-limiting findings without practical abuse or material production impact.
- Social engineering, spam, distributed denial of service, physical attacks, or attacks against Phala employees, users, vendors, or offices.
- Duplicate reports, repeated submissions, or variants that require the same remediation as an existing report.

## Reporting Requirements

To help us evaluate your report, please include:

- The affected production asset, such as the URL, API endpoint, or IP address.
- A clear description of the vulnerability and its security impact.
- Reproducible steps, proof of concept, screenshots, request/response samples, or logs sufficient for us to validate the issue.
- Any limits or assumptions in your testing.

A report qualifies for bounty consideration only when it demonstrates clear, reproducible end-to-end impact in production on an in-scope asset.

## Researcher Rules

When testing and reporting, please:

- Do not access, download, modify, delete, or disclose data beyond what is necessary to demonstrate the vulnerability.
- Do not interrupt, degrade, or deny service to Phala systems or users.
- Do not use social engineering, phishing, spam, physical attacks, or third-party attacks.
- Keep the vulnerability confidential until Phala has resolved it and authorized disclosure.

## What We Promise

- We will acknowledge receipt of your report within 3 business days.
- Full technical assessment, remediation, and any bounty decision may take longer depending on complexity, severity, affected systems, and remediation requirements.
- If you follow this policy, we will not take legal action against you in regard to the report.
- We will handle your report with strict confidentiality and will not pass on your personal details to third parties without your permission.
- We will keep you informed of material progress where practical.
- We will tell you whether the report is accepted as a valid security issue or denied because it is out of scope, not reproducible, already known, or does not demonstrate qualifying security impact.
- In public information concerning the reported issue, we will credit you as the discoverer unless you prefer otherwise.
- As a token of our gratitude, we offer rewards for accepted reports of security issues that were not yet known to us. The type and amount of any reward are determined based on severity, impact, exploitability, report quality, and remediation complexity.

| Severity: | Critical | High     | Medium   | Low       |
| --------- | -------- | -------- | -------- | --------- |
|  Up to:   | $15,000   | $4,500   | $1,500     | $1 - $300 |

Reward amounts will be determined only at the end of remediation of the disclosed issue. Actual reward amounts may exceed $15,000 or be as low as $1. The SYSOPS / CERT Team will provide their assessment and recommendation regarding severity or regarding reward amount but the final decision is solely at the discretion of the Phala Team.

We strive to resolve valid security issues as quickly as practical and would like to play an active role in any publication of the issue after it is resolved.
