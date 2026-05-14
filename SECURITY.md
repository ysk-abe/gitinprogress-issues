# Security Policy

## Reporting a vulnerability

If you discover a security vulnerability in GitInProgress, please **do not
open a public issue**. Instead, report it privately via GitHub's Security
Advisories:

1. Navigate to the [Security tab](../../security/advisories/new) of this repository
2. Click "Report a vulnerability"
3. Fill in the form with as much detail as possible

### What to include

- Description of the vulnerability
- Steps to reproduce
- Affected version of GitInProgress
- Affected version of VS Code
- Potential impact
- (Optional) Suggested fix

### Response timeline

- **Acknowledgment**: within 7 days of receipt
- **Initial assessment**: within 14 days
- **Coordinated disclosure**: timeline agreed with reporter, typically 30-90 days

This is a single-developer project; please be patient.

### Scope

In scope:

- Code execution vulnerabilities in the extension
- Data exposure (e.g., leaking `.git/gitinprogress/` data outside the local repo)
- Authentication bypass for Pro features (when Pro tier launches)
- Vulnerabilities in the bundled MCP server

Out of scope:

- Vulnerabilities in third-party dependencies (please report upstream)
- Issues in development-only files
- Theoretical attacks without practical impact

## Acknowledgments

Reporters who follow this policy and report valid vulnerabilities will be
acknowledged in the release notes (unless they prefer to remain anonymous).
