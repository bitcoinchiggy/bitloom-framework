---
id: 20_key_management_policy
version: 1.0.1
uses: ./00_master_context.md
output: /02_Policies/key_management_policy.md
status: draft
---

## Objective
Generate a GitHub-ready **Key Management Policy** for **[COMPANY NAME]** governing employee handling of private keys, signing, backups, rotation, and incidents.

## Must-use context
- Employees are custodial agents, not beneficial owners.  
- Keys are Company-assigned but physically held by employees.  
- OpsCos retain at least one key in all multisig wallets.  
- Policy must reference: Logging Template, Incident Report Template, Annual Review Checklist.  

## Requirements
- Sections: Purpose, Scope, Roles & Responsibilities, Custody Standards, Signing Procedures, Backup & Resiliency, Key Rotation, Logging & Audit, Confidentiality, Incident Response, Compliance, Revision & Review, Acknowledgment.  
- Must include employee acknowledgment signature block.  
- Markdown format with `##` headings.  

## Constraints
- US English, plain-English.  
- No emojis.  

## Acceptance
- Output must be a standalone `.md` file under `/02_Policies/`.  
