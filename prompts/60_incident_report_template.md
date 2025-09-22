---
id: 60_incident_report_template
version: 1.0.1
uses: ./00_master_context.md
output: /02_Policies/incident_report_template.md
status: draft
---

## Objective
Generate a GitHub-ready **Incident Report Template** for **[COMPANY NAME]** employees to report key-related incidents.

## Must-use context
- Employees act as custodial agents under Company policy.  
- Incidents include: lost/stolen device, suspected compromise, unauthorized signing, backup/resiliency failures.  
- Reports feed into Annual Review process.  

## Requirements
- Sections: Incident Details, Description, Immediate Actions Taken, Impact Assessment, Follow-Up Actions, Supervisor Review, Final Sign-Off, Instructions.  
- Use checkboxes for incident types.  
- Placeholders: [DATE], [NAME], [DETAILS].  

## Constraints
- US English, plain-English.  
- No emojis.  

## Acceptance
- Output must be a standalone `.md` under `/02_Policies/`.  
