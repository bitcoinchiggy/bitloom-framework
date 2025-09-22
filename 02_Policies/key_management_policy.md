# Key Management Policy
**Bitloom LLC**

Effective Date: [DATE]  
Version: 1.0

---

## 1. Purpose
This Key Management Policy establishes standards and procedures for the custody, use, backup, and rotation of cryptographic keys used by Bitloom LLC (“Company”) in providing multisig wallet and licensing services. It ensures keys are protected, auditable, and managed in a way that supports operational security and regulatory defensibility.

---

## 2. Scope
This policy applies to all employees of the Company who are designated **Key Custody & Signing Technicians** (junior or senior). It covers all private keys, seeds, XPUBs, devices, logs, and processes maintained for Company or client operations.

---

## 3. Roles & Responsibilities
- **Employees (Technicians):**  
  - Safeguard private keys assigned to them.  
  - Perform signing only when instructed by the Company.  
  - Complete logging and backup verification duties.  
  - Maintain confidentiality of all cryptographic material.  

- **Senior Technicians:**  
  - Review logs of junior technicians.  
  - Provide training and serve as escalation point.  

- **Supervisor/Manager:**  
  - Construct multisig wallets and transactions.  
  - Coordinate client communications.  
  - Oversee compliance with this Policy.  

---

## 4. Custody Standards
- Keys must be stored only on Company-provided hardware devices.  
- Devices must remain in the physical possession of the assigned Employee.  
- Keys may never be exported, shared, or copied without explicit Company authorization.  
- Custodians act as **agents of the Company**; ownership of Bitcoin always remains with the client (OpsCo).  

---

## 5. Signing Procedures
- Transactions are constructed by the Manager.  
- Signing requests are communicated to designated Technicians.  
- Each signing event must be logged (date, time, purpose, transaction reference).  
- No signing may occur without written or logged Company instruction.  

---

## 6. Backup & Resiliency
- Each key must have backups in accordance with Company backup standards (e.g., encrypted backups stored in multiple secure locations).  
- Technicians must perform quarterly resiliency checks to confirm backup validity.  
- Backup verifications must be logged.  
- Recovery drills shall be conducted annually.  

---

## 7. Key Rotation
- Keys must be rotated [annually/bi-annually] or upon any suspected compromise.  
- Rotation requires issuance of new XPUBs and updating multisig descriptors.  
- Old keys must be securely retired and documented.  

---

## 8. Logging & Audit
- All key events (generation, signing, backup verification, rotation) must be logged using the Company’s standardized Logging Template.  
- Logs must be reviewed monthly by a Senior Technician.  
- Logs must be retained for a minimum of [X] years.  

---

## 9. Confidentiality
- All employees are bound by confidentiality provisions in their Employment Agreement.  
- Private keys, seeds, and device PINs are Company confidential information.  
- Disclosure outside Company authorization is grounds for termination.  

---

## 10. Incident Response
- Any suspected compromise, lost device, or unusual signing activity must be reported immediately.  
- Employees must complete an Incident Report (see Incident Report Template).  
- The Manager will coordinate containment, rotation, and client communication.  

---

## 11. Compliance
Failure to comply with this Policy may result in disciplinary action, up to and including termination of employment.

---

## 12. Revision & Review
This Policy will be reviewed annually and updated as necessary to reflect evolving security practices and regulatory requirements.

---

**Acknowledgment**  
By signing below, Employee acknowledges receipt of this Key Management Policy and agrees to abide by its provisions.

Employee Name: ___________________________  
Signature: ________________________________  
Date: ___________________________________
