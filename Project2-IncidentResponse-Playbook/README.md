# Project 2: Incident Response Playbook – Phishing Scenario  

This project demonstrates the design of an **Incident Response (IR) Playbook** for phishing attacks, aligned with industry standards (**NIST 800-61r2**) and compliance frameworks (**SOC 2, ISO 27001**).  

It provides a structured approach to managing security incidents while maintaining **audit-ready documentation and evidence**.  

---

## Objective  
To create a repeatable and auditable response plan for phishing incidents that ensures:  
- Quick detection and containment of threats  
- Clear assignment of roles and responsibilities  
- Evidence collection for compliance audits  
- Continuous improvement through lessons learned  

---

## Playbook Phases  

| Phase                | Description                                                   | Evidence Examples                         | Owner            |  
|----------------------|---------------------------------------------------------------|-------------------------------------------|------------------|  
| **Preparation**      | Awareness training, phishing simulations, predefined contacts | Training logs, LMS records                 | Compliance       |  
| **Detection**        | SIEM alerting, suspicious email reports, header analysis      | Sentinel alerts, reported emails           | Security Analyst |  
| **Containment**      | Isolate user accounts, block malicious senders/domains        | Entra ID logs, Defender quarantine logs    | IT Security      |  
| **Eradication**      | Remove malicious messages, reset credentials                  | Exchange quarantine reports, reset logs    | IT Security      |  
| **Recovery**         | Restore mailboxes, monitor for reinfection                    | Recovery logs, monitoring dashboards       | Security Ops     |  
| **Lessons Learned**  | Post-incident review, tabletop exercises                      | IR report, meeting notes, action items     | Compliance / CISO|  

---

## Compliance Mapping  
- **SOC 2 CC7.2** – Incident Response procedures established and tested  
- **ISO 27001 A.16** – Management of Information Security Incidents  
- **NIST 800-61r2** – Computer Security Incident Handling Guide  

---

## Deliverables  
- **Incident Response Playbook (Markdown/PDF)** – This README serves as the documentation.  
- **Checklist Template (Excel/PDF)** – Assign responsibilities, track status, and log evidence.  

---

## Next Steps  
- Automate response workflows with **Microsoft Sentinel playbooks (Logic Apps)**  
- Maintain **evidence packs** (redacted screenshots, logs, reports) for audits  
- Conduct quarterly phishing simulations as part of compliance testing  
