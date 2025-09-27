# Project 1: SIEM Log Investigation – Brute Force Detection  

This project demonstrates the use of a **Security Information and Event Management (SIEM)** system to detect brute force authentication attempts.  
It combines **technical investigation** with **risk management deliverables**, showing how security monitoring supports both **incident response** and **compliance requirements**.  

---

## Objective  
- Detect and investigate brute force authentication attempts.  
- Demonstrate how **Microsoft Sentinel** queries can surface suspicious activity.  
- Document findings in an **incident report** aligned with compliance frameworks.  
- Map risks and controls in a **risk register** for GRC readiness.  

---

## Investigation Steps  

1. **Log Source Integration**  
   - Collected authentication logs from Microsoft 365 / Active Directory.  
   - Ingested logs into Microsoft Sentinel.  

2. **Detection Query (KQL)**  
```kql
SecurityEvent
| where EventID == 4625
| summarize FailedLogins = count() by Account, IPAddress, bin(TimeGenerated, 5m)
| where FailedLogins > 10
