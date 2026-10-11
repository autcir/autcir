# Security Policy

This repository is a GitHub profile: Markdown, one SVG and a few workflows. The
security-relevant surface is the workflows in `.github/workflows/`, the
dependencies they use, and anything that must never be committed (credentials).

## Reporting a Vulnerability

**Please do not open a public issue with details.**

1. Use [Report a vulnerability](https://github.com/autcir/autcir/security/advisories/new)
   (Security tab of this repository). Include what is affected, what an attacker
   could achieve, and how to reproduce it.
2. If that button is not available, open a public issue that only says you need
   a private channel for a security report, with no technical details, and a
   channel will be arranged there.

Expect an initial response within 7 days.

## Supported Versions

Only `main` and the latest tagged release receive fixes; older tags do not.

## Secrets

This repository must never contain credentials. History and new changes are
scanned with [gitleaks](https://github.com/gitleaks/gitleaks). If you find a
committed secret, report it privately as above and do not quote its value in a
public issue.

## Supply chain

Every GitHub Action is pinned to a full commit SHA and updated through
Dependabot (with a cooldown) rather than floating tags.
