# Threat Model Diagram

```mermaid
flowchart TD
    A[Threats] --> B[Unauthorized Account Access]
    A --> C[Accidental File Deletion]
    A --> D[Malicious Code Changes]
    A --> E[Asset Theft]
    B --> F[Strong Password and MFA]
    C --> G[Git History and Independent Backups]
    D --> H[Code Review and Branch Controls]
    E --> I[Restricted Access and Watermarking]
```

## Purpose
This diagram links potential threats to planned mitigation measures.

## Important
These are proposed controls. Their actual configuration and effectiveness must be verified separately.
