---
id: 70_diagrams
version: 1.0.1
uses: ./00_master_context.md
output:
  - /05_Diagrams/wallet_design_matrix.mmd
  - /05_Diagrams/org_chart.mmd
status: draft
---

## Objective
Generate Mermaid diagrams visualizing **[COMPANY NAME]** custody model and organizational roles.

## Must-use context
- OpsCo remains legal owner of Bitcoin and must hold ≥1 key.  
- [COMPANY NAME] coordinates multisig XPUBs but has no unilateral custody.  
- Senior Technician supervises juniors, reviews logs, assists in incidents.  
- Employees act as custodial agents, not beneficial owners.  

## Requirements

### 1. Wallet Design Matrix (`wallet_design_matrix.mmd`)
- Flowchart showing OpsCo, [COMPANY NAME], Senior, Junior roles.  
- Annotate multisig models (2-of-3 recommended, 3-of-5 optional).  
- Include sequence diagram showing transaction signing flow.  
- Add compliance/logging hooks in comments.  

### 2. Org Chart (`org_chart.mmd`)
- Hierarchical: [COMPANY NAME] → Manager → Senior Tech → Junior Tech.  
- OpsCo shown as client, not subordinate.  
- Cross-link to Key Management Policy in diagram notes.  

## Constraints
- Mermaid syntax only.  
- Copy-paste safe, no emojis.  
- Include classDef styles for clarity.  

## Acceptance
- Output must be standalone `.mmd` files under `/05_Diagrams/`.  
- Must align with master context and policies.  
