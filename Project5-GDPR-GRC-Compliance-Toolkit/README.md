# Project 5: GDPR GRC Compliance Toolkit

This project demonstrates a practical **GDPR (General Data Protection Regulation)** toolkit for Governance, Risk, and Compliance (GRC).  
It includes a risk register mapped to GDPR Articles, a control matrix for key requirements, and audit-ready evidence tracking.

---

## Objective
- Map GDPR requirements to concrete controls and evidence.
- Identify and track privacy risks with **Likelihood/Impact/Inherent/Residual** scoring.
- Provide **audit-ready deliverables** (Excel + PDF) suitable for client packs and interviews.

---

## Deliverables
- **Risk Register (Excel)** – [GDPR_Risk_Register_Expanded.xlsx](./GDPR_Risk_Register.xlsx)  
  Ten GDPR risks with scoring, controls, residual risk, and treatment plans.
- **Compliance Report (PDF)** – [GDPR_Compliance_Report.pdf](./GDPR_Compliance_Report.pdf)  
  Concise mapping of risks to GDPR Articles with next steps.

---

## How to Use
1. Open the Excel **Risk Register** and adjust Likelihood/Impact to fit your environment.
2. Link each risk to **controls** (privacy policy, consent, encryption, DSAR, DPIA, breach SOP).
3. Attach **evidence** (policies, screenshots, logs, training records).
4. Track **Treatment Plans** and update **Residual Risk** after mitigation.

---

## Example GDPR Mapping (mini control matrix)

| GDPR Article | Requirement (short)                                | Example Controls                                  | Evidence (examples)                       | Owner     |
|--------------|-----------------------------------------------------|---------------------------------------------------|-------------------------------------------|-----------|
| Art. 5       | Lawful, fair, transparent; storage limitation      | Privacy Policy, data minimization, retention      | Policy v2.0, RoPA extract, retention log  | DPO       |
| Art. 30      | Records of Processing (RoPA)                        | Data inventory/registry                           | RoPA.xlsx, system owners list             | Compliance|
| Art. 32      | Security of processing                               | Encryption, RBAC/MFA, logging/monitoring          | Config screenshots, access logs, SIEM     | IT Sec    |
| Art. 33      | Breach notification within 72h                      | IR Playbook, breach notification SOP              | IR report, tabletop results               | DPO       |
| Art. 35      | DPIA for high-risk processing                       | DPIA procedure, risk assessments                   | DPIA template, approvals                  | DPO       |
| Arts. 15–22  | Data subject rights (access, erasure, etc.)         | DSAR workflow, identity verification               | DSAR tickets, SLA dashboard               | Support   |

---

## Example Risks (from the Excel register)

| Risk ID  | Risk Description                                          | Inherent | Residual | Treatment Plan (short)                          |
|---------|------------------------------------------------------------|----------|----------|------------------------------------------------|
| GDPR-001| Non-compliance with lawful/transparent processing (Art.5)  | High     | Medium   | Quarterly privacy audits; consent log reviews  |
| GDPR-004| Missed 72h breach notification (Art.33)                    | High     | Medium   | IR tabletop; notification drills               |
| GDPR-008| Missing DPIA for high-risk processing (Art.35)             | Medium   | Low      | DPIA workflow; approvals required              |
| GDPR-010| Vendor non-compliance with GDPR (Art.28)                   | High     | Medium   | DD reviews; DPAs; annual attestations          |

- [GDPR_Risk_Register.xlsx](./GDPR_Risk_Register.xlsx) – Editable Excel risk register with 10 risks, likelihood/impact scoring, controls, residual risk, and treatment plans.
- [GDPR_Compliance_Report.pdf](./GDPR_Compliance_Report.pdf) – PDF report with compliance mapping to GDPR Articles and recommended next steps. 

---

## Next Steps
- Expand mapping to more Articles (consent, children’s data, cross-border transfers).
- Add **evidence packs** (redacted screenshots, logs, training records).
- Link this toolkit to your **enterprise risk register** and **IR Playbook**.
- Integrate into a GRC platform (OneTrust / ServiceNow / Archer) for workflows.

---

## Notes
- This toolkit aligns with **ISO 27001 Annex A**, **SOC 2 TSC (Security/Confidentiality/Privacy)**, and the **NIST Privacy Framework**.
