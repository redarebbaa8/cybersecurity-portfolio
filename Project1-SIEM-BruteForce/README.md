# Project 1: SIEM Log Investigation – Brute Force Detection  

This project demonstrates the use of a **Security Information and Event Management (SIEM)** system to detect brute force authentication attempts.  
The investigation highlights how logs can be leveraged for **security monitoring, evidence collection, and compliance reporting**.  

---

## Objective  
To investigate suspicious login activity, identify brute force attacks, and demonstrate how SIEM capabilities support both **incident response** and **compliance requirements**.  

---

## Investigation Steps  

1. **Log Source Integration**  
   - Collected authentication logs from Microsoft 365 / Active Directory.  
   - Ingested into Microsoft Sentinel.  

2. **Detection Query (KQL)**  
```kql
SecurityEvent
| where EventID == 4625
| summarize FailedLogins = count() by Account, IPAddress, bin(TimeGenerated, 5m)
| where FailedLogins > 10
