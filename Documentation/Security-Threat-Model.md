# Security Threat Model

## Assets to Protect
- Source code
- Project documentation
- Media assets
- GitHub account and repository access

## Potential Threats
1. Unauthorized account access
2. Accidental deletion or modification of files
3. Malicious code changes
4. Exposure of private information
5. Theft or unauthorized reuse of media assets

## Mitigation Measures
- Use strong, unique passwords and multi-factor authentication.
- Restrict repository permissions according to user roles.
- Review changes before merging pull requests.
- Keep independent backups of important files.
- Never commit passwords, API keys, or access tokens.
- Use digital watermarks to help identify asset ownership.

## Recovery
Use Git history and independent backups to restore affected files.

## Scope
This document describes potential threats and planned mitigations. It is not a completed security audit.
