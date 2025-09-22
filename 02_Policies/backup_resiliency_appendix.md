# Backup & Resiliency Appendix
**[COMPANY NAME]**

Effective Date: [DATE]  
Version: 1.0

---

## Purpose
This appendix supplements the Key Management Policy by providing detailed standards for the backup, verification, and recovery of cryptographic keys and devices. It ensures resiliency in the event of device loss, compromise, or disaster.

---

## 1. Backup Standards
- Each private key must have at least **two backups** stored in geographically distinct locations.  
- Backups must be encrypted and labeled with a Key ID (not the seed itself).  
- Backup media (e.g., hardware wallet SD card, encrypted USB, or paper seed) must be stored in fireproof and tamper-evident containers.  
- Access to backup locations is restricted to Manager and designated Senior Technician.  

---

## 2. Verification Schedule
- **Quarterly Verification:**  
  Each Technician must verify that backups are present and intact. Verification must be logged in the Backup Verification Log.  
- **Annual Full Restore Test:**  
  At least once per year, the Manager will conduct a full test restore from backup to confirm operational readiness. Results must be logged in the Resiliency Drill Log.  

---

## 3. Resiliency Drills
- **Scope:** Recovery of keys/devices, replacement of lost/stolen hardware, and validation of signing capability.  
- **Participants:** Manager, Senior Technician, and designated Junior Technicians.  
- **Frequency:** Annual (minimum).  
- **Documentation:** Outcomes, issues, and corrective actions must be logged and reviewed.  

---

## 4. Incident Response Integration
- In the event of an incident (compromise, device loss, suspected theft), this appendix provides the procedures for immediate backup use and key rotation.  
- Incident Reports must reference backup status and resiliency test outcomes.  

---

## 5. Review & Updates
- This appendix must be reviewed annually alongside the Key Management Policy.  
- Any changes must be approved by Manager and documented in the Annual Review Checklist.  

---

**Acknowledgment**  
By signing below, Employee acknowledges receipt of this appendix and agrees to comply with its requirements.

Employee Name: __________________________  
Signature: _______________________________  
Date: ___________________________________
