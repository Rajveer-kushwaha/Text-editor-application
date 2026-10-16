# Tools & Techniques of Games and VFX-II
## Assignment-I: Repository Governance, Asset Management and Security

**Project:** Text Editor Application  
**Student:** Rajveer  
**Repository:** Text-Editor-Application

## 1. Objectives
- Establish a structured GitHub repository.
- Demonstrate branching and issue tracking.
- Document digital asset management and Git LFS.
- Plan secure access, threat mitigation, and watermarking.
- Design cloud storage, backup, and recovery strategies.

## 2. Repository Governance
The repository contains Documentation, Source, Assets, Reports, and Screenshots folders. The planned branching strategy uses main for the stable version, development for ongoing work, and feature for isolated changes.

## 3. Issue Tracking
Three issue templates were created for bug reports, feature requests, and project tasks. A GitHub project board was created to organize work by status.

## 4. Asset Management
The Assets folder is intended to store media resources. Git LFS is documented as a proposed approach for large binary files such as 3D models, textures, audio, and video.

## 5. Version Control and Recovery
Git tracks file changes and commit history. The documented recovery process includes reviewing history, restoring required files, and testing after recovery. Independent backups should be maintained separately.

## 6. Security and Threat Model
Potential threats include unauthorized account access, accidental deletion, malicious code changes, and asset theft. Proposed controls include strong passwords, MFA, access restrictions, code review, backups, and watermarking.

## 7. Cloud Storage Architecture
The architecture document describes the developer computer, GitHub repository, version history, proposed large-file storage, and independent backups.

## 8. Digital Watermarking
The watermarking report describes visible and invisible watermarks, ownership records, and watermarked previews for shared media.

## 9. Cost Optimization
The report recommends avoiding duplicate files, using Git LFS selectively, compressing suitable assets, and reviewing storage limits and pricing.

## 10. Practical Scenarios
1. **Accidental deletion:** inspect Git history or restore from an independent backup.
2. **Unauthorized account access:** secure the account using MFA and review access permissions.
3. **Large media files:** evaluate Git LFS or separate cloud storage and maintain a backup.

## 11. Conclusion
The repository provides a structured foundation for demonstrating repository governance, version control, issue tracking, asset management, and security planning. Proposed controls and services must be configured and tested before they can be claimed as implemented.

## 12. References
- GitHub Docs: https://docs.github.com/
- Git LFS: https://git-lfs.com/
- Git Documentation: https://git-scm.com/doc/
