---
id: 80_review_docs
version: 1.0.1
uses: ./00_master_context.md
output:
  - /06_Review/annual_review_checklist.md
  - /06_Review/supervisor_training_notes.md
status: draft
---

## Objective
Generate GitHub-ready review and oversight documents for **[COMPANY NAME]**, including the Annual Review Checklist and Supervisor Training Notes.

## Must-use context
- Senior Technician supervises juniors and reviews logs.  
- Annual Review ensures IRS defensibility and operational security.  
- Policies cross-reference Logging Template, Incident Reports, Compensation Memo, and Custody Statement.  

## Requirements
1. **Annual Review Checklist**  
   - Sections: Policy Review, Employment & Compensation, Logging & Audit, Incident Management, Custody & Ownership, Technical Ops, Governance, Sign-Off.  
   - Use checkboxes.  
   - Placeholders: [DATE], [X years].  

2. **Supervisor Training Notes**  
   - Duties: oversight, training, incident support, communication, annual review role.  
   - Include Do’s and Don’ts.  
   - Signature acknowledgment section.  

## Constraints
- US English, plain-English.  
- No emojis.  

## Acceptance
- Output must be standalone `.md` files under `/06_Review/`.  
