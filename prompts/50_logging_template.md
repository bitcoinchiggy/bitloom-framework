---
id: 50_logging_template
version: 1.0.1
uses: ./00_master_context.md
output: /02_Policies/logging_template.md
status: draft
---

## Objective
Generate a GitHub-ready **Logging Template** for **[COMPANY NAME]** employees to document all key management activities.

## Must-use context
- Activities to log: signing, backups, resiliency drills, key rotations, reviews.  
- Senior Technician must review logs monthly.  
- Logs retained for [X] years.  

## Requirements
- Sections: Signing Log, Backup Verification Log, Resiliency Drill Log, Key Rotation Log, Review & Sign-Off.  
- Use Markdown tables.  
- Placeholders: [MM/DD/YY], [Name], [TxID].  

## Constraints
- US English, plain-English.  
- No emojis.  

## Acceptance
- Output must be a standalone `.md` under `/02_Policies/`.  
