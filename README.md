##  Azure-Based Secure Backup and Disaster Recovery Architecture

This project focuses on designing and implementing a secure cloud-based backup and disaster recovery solution using Microsoft Azure for protecting critical healthcare data.



### 🔹 Key Features & Implementation

- Designed and implemented a secure Azure-based backup and disaster recovery architecture using **Azure Virtual Machines**, **Recovery Services Vault**, and **Azure Backup**, ensuring high availability and protection of critical healthcare data.

- Configured automated backup policies with **incremental snapshots**, **geo-redundant storage (GRS)**, and defined **Recovery Point Objective (RPO)** and **Recovery Time Objective (RTO)** to enable reliable data recovery and business continuity.

- Implemented monitoring and logging using **Azure Monitor** and **Log Analytics Workspace**, creating **metric-based and log-based alert rules** integrated with action groups for real-time incident notification.

- Deployed **Microsoft Sentinel (SIEM/SOAR)** for advanced security monitoring and developed **KQL-based analytics rules** to detect:
  - Suspicious login attempts (brute-force attacks)
  - Critical administrative activities  
  *(aligned with MITRE ATT&CK framework)*

- Applied network-level security using **Network Security Groups (NSG)** by configuring inbound access rules to restrict traffic and reduce the attack surface.

### 🔹 Architecture Highlights

- Secure integration of **on-premises systems with Azure cloud**
- Automated backups every 4 hours with retention policies
- Centralized logging and monitoring for full visibility
- Role-Based Access Control (RBAC) and Multi-Factor Authentication (MFA)
- Protection against data loss, cyber threats, and system failures

### 🔹 Outcome

This solution enhances:
-  Data security (Confidentiality, Integrity, Availability)
- System resilience and uptime
-  Reliable disaster recovery capability
- Real-time monitoring and threat detection


