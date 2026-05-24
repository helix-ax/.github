# Security Policy

Helix takes vulnerability reporting seriously. If you believe you have found a
security issue in a Helix repository, service, domain, or public-facing asset,
report it privately before sharing details publicly.

## Reporting A Vulnerability

Email security@helix.ax with a concise report that includes:

- the affected repository, service, endpoint, or domain;
- a clear description of the issue and likely impact;
- reproduction steps or proof-of-concept details, when safe to share;
- any relevant logs, screenshots, request IDs, or timestamps with sensitive
  values removed;
- your preferred contact information for follow-up.

Do not report security issues through public GitHub issues, pull requests,
discussion threads, or social channels.

## Scope

This policy applies to Helix-owned GitHub repositories and public Helix assets
that are intentionally published by the organization.

Most Helix engineering repositories are private while the platform is under
active development. Pre-release code, internal prototypes, and non-production
systems may change quickly and may not have production security guarantees.

## Sensitive Information

Do not include secrets, access tokens, private keys, customer data, personal
data, or sensitive logs in reports. If sensitive material is required to explain
the issue, describe what is available and wait for a secure handling path before
sending it.

If you discover exposed credentials, report the location and evidence needed to
identify the exposure without copying or using the credential.

## Coordinated Disclosure

Helix asks reporters to give us reasonable time to investigate and remediate
valid issues before public disclosure. We will review incoming reports,
prioritize them based on impact and exploitability, and follow up through the
contact path used for the report.

Do not attempt persistence, data extraction, privilege expansion, lateral
movement, denial of service, social engineering, or physical attacks.

## Public Contact

- Security reports: security@helix.ax
- Administrative inquiries: admin@helix.ax
- General inquiries: hello@helix.ax
