---
id: 10_employment_agreement
version: 1.0.1
uses: ./00_master_context.md
output: /01_Employment/employment_agreement_template.md
status: draft
---

## Objective
Generate a GitHub-ready Employment Agreement for "Key Custody & Signing Technician" (junior & senior) using master context.

## Must-use context
- Employer is **[COMPANY NAME]**, a parent-owned LLC.  
- Employees are custodial agents, not beneficial owners.  
- Wages fall in the \$8,000–\$14,000 range depending on role.  

## Requirements
- Sections: Position, Duties & Responsibilities, Compensation, Work-for-Hire & IP, Equipment & Devices, Confidentiality, Termination, Governing Law, Entire Agreement, Signatures.  
- Add senior variant with supervisory duties.  
- Use placeholders like [STATE], [DATE], [AMOUNT].  
- Markdown format with `##` headings.  

## Constraints
- US English, plain-English legal drafting.  
- No emojis.  
- Must align with master context and reference Key Management Policy.  

## Acceptance
- Output must be a standalone `.md` file under `/01_Employment/`.  
