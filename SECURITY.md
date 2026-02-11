# Security Policy

## Reporting a Vulnerability

**Do not report security vulnerabilities through public GitHub issues.**

Use GitHub's private vulnerability reporting:

1. Go to the [Security Advisories page](https://github.com/terminallm-issues/.github/security/advisories/new)
2. Fill in the vulnerability details
3. Submit — only repository maintainers can see the report

We will acknowledge receipt within 48 hours and provide a timeline for a fix.

## Scope

The following are in scope:
- SSH credential handling and storage
- Credential vault encryption
- Authentication bypass (MFA, biometrics)
- Data leakage (credentials, private keys, terminal content)
- Clipboard security
- Server-side file permission issues

## Out of Scope

- Issues in third-party dependencies (report to the upstream project)
- Social engineering attacks
- Physical device access attacks
