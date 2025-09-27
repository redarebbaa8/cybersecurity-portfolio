# Project 3: Microsoft 365 Security & Compliance Risk Assessment  

This project demonstrates a **risk assessment of Microsoft 365 (M365)** services, focusing on security and compliance risks.  
The assessment identifies potential threats, evaluates their likelihood and impact, and maps them to controls and frameworks (SOC 2, ISO 27001, NIST 800-53).  

---

## Objective  
To perform a structured risk assessment for Microsoft 365 by:  
- Identifying security & compliance risks across Exchange Online, SharePoint, OneDrive, and Teams  
- Assessing **Likelihood** and **Impact** to prioritize risks  
- Mapping risks to **controls & compliance frameworks**  
- Documenting mitigation measures and responsible owners  

---

## Risk Assessment Matrix  

| Risk ID | Risk Description | Likelihood | Impact | Residual Risk | Control/Mitigation | Owner |  
|---------|-----------------|------------|--------|---------------|--------------------|-------|  
| M365-001 | Unauthorized access due to weak MFA enforcement | Medium | High | Medium | Enforce Conditional Access & MFA across tenants | IT Security |  
| M365-002 | Data loss via unmanaged personal devices (BYOD) | High | Medium | High | Implement MAM/MDM policies, DLP controls | Compliance & IT |  
| M365-003 | Phishing via Teams/Exchange | High | High | High | Defender for O365, Safe Links/Safe Attachments | Security Ops |  
| M365-004 | Misconfigured SharePoint permissions | Medium | Medium | Medium | Regular access reviews, least privilege model | Business Owners |  

---

## Compliance Mapping  
- **SOC 2 CC6.1** – Logical access controls (MFA, RBAC)  
- **SOC 2 CC7.2** – Incident detection & response (Defender alerts, playbooks)  
- **ISO 27001 A.9** – Access control policies and user management  
- **ISO 27001 A.12** – Logging, monitoring, and event management  
- **NIST 800-53 AC-2 / AU-6** – Access control and audit logging  

---

## Deliverables  
- **Risk Assessment Register**  
  - [M365_Risk_Assessment.xlsx](./M365_Risk_Assessment.xlsx) – Editable risk register with filters, scoring, and mitigation tracking  
  - [M365_Risk_Assessment.pdf](./M365_Risk_Assessment.pdf) – Polished PDF version for presentation/audit packs  

---

## Next Steps  
- Automate risk monitoring with **Microsoft Secure Score & Compliance Manager**  
- Link risks to actual **policy & procedure documents** (Access Control Policy, DLP Policy, etc.)  
- Expand assessment to cover **Availability, Confidentiality, Privacy** Trust Services Criteria (TSC)  
- Integrate with an **organization-wide risk register** for central GRC reporting  

---
