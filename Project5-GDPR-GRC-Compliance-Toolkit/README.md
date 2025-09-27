# Project 5: GDPR GRC Compliance Toolkit

This project provides a practical **GDPR (General Data Protection Regulation)** toolkit tailored for Governance, Risk, and Compliance (GRC).  
It combines a structured risk register, control matrix, and compliance report to support audit readiness and client-facing deliverables.

---

## Objective
- Map GDPR Articles to **implementable controls** and audit evidence.  
- Track privacy risks with **Likelihood, Impact, Inherent, and Residual** scoring.  
- Deliver **audit-ready outputs** (Excel + PDF) for interviews, assessments, or client packs.  

---

## Deliverables
- [GDPR_Risk_Register.xlsx](./GDPR_Risk_Register.xlsx) – Risk register with 10 GDPR risks, scoring, controls, residual risk, and treatment plans.  
- [GDPR_Compliance_Report.pdf](./GDPR_Compliance_Report.pdf) – Report mapping GDPR Articles to controls, with next steps and evidence guidance.  

---

## How to Use
1. Open the **Excel Risk Register** and update Likelihood/Impact values for your environment.  
2. Link each risk to specific **controls** (privacy policies, consent mechanisms, encryption, DSAR workflows, DPIA, breach response).  
3. Attach or reference **evidence** (policies, logs, screenshots, training records).  
4. Track **Treatment Plans** and re-evaluate **Residual Risk** post-mitigation.  

---

## GDPR Control Mapping (Excerpt)

| GDPR Article | Requirement (short)                           | Example Controls                               | Evidence (examples)                  | Owner     |
|--------------|-----------------------------------------------|------------------------------------------------|--------------------------------------|-----------|
| Art. 5       | Lawful, fair, transparent; storage limitation | Privacy Policy, data minimization, retention   | Policy v2.0, RoPA extract, retention log | DPO       |
| Art. 30      | Records of Processing (RoPA)                  | Data inventory/registry                        | RoPA.xlsx, system owners list        | Compliance|
| Art. 32      | Security of processing                        | Encryption, RBAC/MFA, SIEM monitoring          | Config screenshots, access logs, SIEM| IT Sec    |
| Art. 33      | Breach notification within 72h                | IR Playbook, breach notification SOP           | IR report, tabletop results          | DPO       |
| Art. 35      | DPIA for high-risk processing                 | DPIA process and approvals                     | DPIA template, review logs           | DPO       |
| Arts. 15–22  | Data subject rights (DSAR)                    | DSAR workflow, ID verification, SLA tracking   | DSAR tickets, SLA dashboard          | Support   |

---

## Risk Register Highlights (from Excel)

| Risk ID  | Risk Description                                  | Inherent | Residual | Treatment Plan (short)                |
|----------|--------------------------------------------------|----------|----------|---------------------------------------|
| GDPR-001 | Non-compliance with lawful/transparent processing (Art.5) | High     | Medium   | Privacy audits, consent log reviews   |
| GDPR-004 | Missed 72h breach notification (Art.33)           | High     | Medium   | IR tabletop exercises, drills         |
| GDPR-008 | Missing DPIA for high-risk processing (Art.35)    | Medium   | Low      | DPIA workflow with approvals          |
| GDPR-010 | Vendor non-compliance with GDPR (Art.28)          | High     | Medium   | Due diligence, DPAs, vendor attestations |

*(Full list available in the Excel file.)*  

---

## Next Steps
- Expand coverage to additional GDPR Articles (consent, children’s data, cross-border transfers).  
- Build **evidence packs** (training certificates, screenshots, breach reports).  
- Link GDPR risk register to the **enterprise-wide risk framework**.  
- Integrate into GRC platforms (OneTrust, Archer, ServiceNow) for workflow automation.  

---

## Notes
- Toolkit aligns with **ISO 27001 Annex A**, **SOC 2 TSC (Security, Confidentiality, Privacy)**, and the **NIST Privacy Framework**.
- Designed for **client deliverables, interviews, and audit preparation**.   
