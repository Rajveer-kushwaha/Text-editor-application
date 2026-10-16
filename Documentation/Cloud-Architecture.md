# Cloud Storage Architecture Diagram

```mermaid
flowchart TD
    A[Developer Computer] --> B[Git and GitHub Repository]
    B --> C[Version History]
    B --> D[Source Code and Documentation]
    A --> E[Large Media Assets]
    E --> F[Git LFS or Cloud Storage]
    F --> G[Independent Backup]
    H[Strong Password and MFA] --> B
```

## Explanation
- Developer Computer: edits source code and assets.
- GitHub Repository: stores tracked files and version history.
- Git LFS or Cloud Storage: planned storage for large binary files.
- Independent Backup: separate recovery copy.
- Strong Password and MFA: protects account access.

Note: Git LFS, external cloud storage, and independent backup are proposed components unless separately configured and verified.
