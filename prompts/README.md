# Bitloom Prompt Library

This folder contains **prompt files** used to consistently generate and regenerate the key documents of the Bitloom Framework. Each prompt references the **master context** to ensure consistency across employment, contracts, policies, memos, diagrams, and review materials.

---

## 📂 Prompt Index

### 00 – Master Context
- **File:** `00_master_context.md`  
- **Purpose:** Defines project purpose, tax/legal positions, glossary, style rules.  
- **Dependencies:** All other prompts reference this file.  

### 10 – Employment Agreement
- **File:** `10_employment_agreement.md`  
- **Output:** `/01_Employment/employment_agreement_template.md`  
- **Purpose:** Generates junior + senior Employment Agreements for **[COMPANY NAME]**, with custodial clause and references to Key Management Policy.  

### 20 – Key Management Policy
- **File:** `20_key_management_policy.md`  
- **Output:** `/02_Policies/key_management_policy.md`  
- **Purpose:** Generates full Key Management Policy for **[COMPANY NAME]**, covering custody, signing, backups, rotation, logging, confidentiality, and incidents.  

### 30 – OpsCo License Agreement
- **File:** `30_opsco_license_agreement.md`  
- **Output:** `/03_Contracts/opsco_license_agreement.md`  
- **Purpose:** Generates License & Services Agreement for **[COMPANY NAME]** and OpsCo, ensuring OpsCo remains legal owner of Bitcoin.  

### 40 – Reasonable Compensation Memo
- **File:** `40_reasonable_compensation_memo.md`  
- **Output:** `/04_Memos/reasonable_compensation_memo.md`  
- **Purpose:** Documents IRS-defensible compensation ranges (\$8k–\$14k) for junior and senior technicians employed by **[COMPANY NAME]**.  

### 50 – Logging Template
- **File:** `50_logging_template.md`  
- **Output:** `/02_Policies/logging_template.md`  
- **Purpose:** Generates Markdown tables for **[COMPANY NAME]** employees to log signing, backups, resiliency drills, rotations, and reviews.  

### 60 – Incident Report Template
- **File:** `60_incident_report_template.md`  
- **Output:** `/02_Policies/incident_report_template.md`  
- **Purpose:** Creates standardized form for **[COMPANY NAME]** employees to report incidents like lost devices, compromises, unauthorized signing, or backup failures.  

### 70 – Diagrams
- **File:** `70_diagrams.md`  
- **Output:** `/05_Diagrams/wallet_design_matrix.mmd`, `/05_Diagrams/org_chart.mmd`  
- **Purpose:** Generates Mermaid diagrams showing **[COMPANY NAME]** wallet design, signing flow, and org chart.  

### 80 – Review Docs
- **File:** `80_review_docs.md`  
- **Output:** `/06_Review/annual_review_checklist.md`, `/06_Review/supervisor_training_notes.md`  
- **Purpose:** Generates review docs for **[COMPANY NAME]**, including the annual compliance checklist and supervisor training notes.  

---

## 🔑 Usage
- Each prompt references `00_master_context.md`.  
- Prompts specify **output paths** so generated files always land in the correct folder.  
- Use these prompts with ChatGPT or other LLM tooling to regenerate documents as policies evolve.  

