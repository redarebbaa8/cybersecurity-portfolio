# Project 2: Incident Response Playbook – Phishing Scenario  

This project demonstrates the design of an **Incident Response (IR) Playbook** for phishing attacks.  
It is aligned with industry standards (**NIST SP 800-61r2**) and compliance frameworks (**SOC 2, ISO 27001**).  

The playbook provides a structured, audit-ready process for handling phishing incidents while ensuring that evidence is collected and mapped to compliance requirements.  

---

## Objective  
To create a repeatable and auditable response plan for phishing incidents that ensures:  
- Timely detection and containment of threats  
- Clear assignment of roles and responsibilities  
- Documentation of evidence for audits  
- Continuous improvement through lessons learned  

---

## Playbook Phases  

| Phase                | Description                                                   | Evidence Examples                         | Owner            |  
|----------------------|---------------------------------------------------------------|-------------------------------------------|------------------|  
| **Preparation**      | Awareness training, phishing simulations, predefined contacts | Training logs, LMS records                 | Compliance       |  
| **Detection**        | Identify phishing emails via SIEM alerts, user reports        | Sentinel alerts, reported email headers    | Security Analyst |  
| **Containment**      | Isolate accounts, block malicious senders/domains             | Entra ID logs, Defender quarantine logs    | IT Security      |  
| **Eradication**      | Remove malicious messages, reset credentials                  | Quarantine reports, password reset logs    | IT Security      |  
| **Recovery**         | Restore mailboxes, monitor for reinfection                    | Recovery logs, monitoring dashboards       | Security Ops     |  
| **Lessons Learned**  | Post-incident review, tabletop exercises                      | IR report, meeting notes, action items     | Compliance / CISO|  

---

## Compliance Mapping  
- **SOC 2 CC7.2** – Incident response procedures established and tested  
- **ISO 27001 A.16** – Management of Information Security Incidents  
- **NIST SP 800-61r2** – Computer Security Incident Handling Guide  

---

## Deliverables  
- **Incident Response Playbook (Markdown/PDF)** – This README provides the documentation.  
- **Checklist Template (Excel/PDF)** – Assign responsibilities, track status, and log evidence.  

---

## Next Steps  
- Automate response workflows using **Microsoft Sentinel playbooks (Logic Apps)**  
- Maintain **evidence packs** (redacted logs, screenshots, reports) for audits  
- Conduct **quarterly phishing simulations** as part of compliance testing  
