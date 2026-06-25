# Cybersecurity-Portfolio
## 🔐 Overview
This repository contains automation scripts and workflows for SOC operations, log parsing, and incident response.  
Aligned with my professional experience in **SIEM (Splunk, Microsoft Sentinel)**, **EDR (CrowdStrike)**, and **vulnerability management (Qualys, Nessus)**.

# SOC Automation Scripts

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](ca://s?q=Add_build_status_badge_to_GitHub_repo)
[![Security Scan](https://img.shields.io/badge/security-snyk-blue)](ca://s?q=Add_security_scan_badge_to_GitHub_repo)
[![License](https://img.shields.io/badge/license-MIT-yellow)](ca://s?q=Add_license_badge_to_GitHub_repo)
[![Languages](https://img.shields.io/badge/languages-Python%20%7C%20PowerShell%20%7C%20Bash-orange)](ca://s?q=Add_programming_language_badge_to_GitHub_repo)


```
##📂 Repository Structure
```text
/scripts
    log_parser.py
    vuln_validation.ps1
/playbooks
    mitre_attack_mapping.md
/docs
    incident_response_template.md
    ```

### 🚀 *Getting Started*
### Clone the repo
- Install dependencies (pip install -r requirements.txt)
- Run scripts with sample log files in /data
- Review Mermaid diagrams in README for workflow context

### 🔮 *Future Work*
- Splunk detection queries
- AWS GuardDuty automation scripts
- Compliance audit dashboards
----
## 📜 License
MIT License — free to use and adapt with attribution.

```
## 🌐 Connect with Me

[![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/ennduka86-spec)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/ejikeme-nduka-06633a66/)
[![Email](https://img.shields.io/badge/Email-Contact-red?logo=gmail)](mailto:ennduka86@gmail.com)

```

## ⚙️ Features
- Automated log parsing for high‑volume SOC alerts  
- MITRE ATT&CK technique mapping for detection rules  
- Cloud security posture checks (AWS GuardDuty, Azure Defender)  
- Vulnerability remediation validation scripts  

```

## 📊 Workflow Diagram (Mermaid)

### Incident Response Lifecycle
```mermaid
flowchart TD
    A[Alert]:::red --> B[Triage]:::orange --> C[Escalation]:::yellow --> D[Containment]:::green --> E[Eradication]:::lightblue --> F[Recovery]:::blue --> G[Lessons]:::purple

    classDef red fill:#ff4d4d,color:#fff,stroke:#333,stroke-width:1px;
    classDef orange fill:#ffa64d,color:#fff,stroke:#333,stroke-width:1px;
    classDef yellow fill:#ffeb3b,color:#000,stroke:#333,stroke-width:1px;
    classDef green fill:#4caf50,color:#fff,stroke:#333,stroke-width:1px;
    classDef lightblue fill:#03a9f4,color:#fff,stroke:#333,stroke-width:1px;
    classDef blue fill:#3f51b5,color:#fff,stroke:#333,stroke-width:1px;
    classDef purple fill:#9c27b0,color:#fff,stroke:#333,stroke-width:1px;

```
### Vulnerability Management Flow
```mermaid
flowchart LR
    A[Scan]:::red --> B[Prioritize]:::orange --> C[Remediate]:::yellow --> D[Validate]:::green --> E[Report]:::blue

    classDef red fill:#ff4d4d,color:#fff,stroke:#333,stroke-width:1px;
    classDef orange fill:#ffa64d,color:#fff,stroke:#333,stroke-width:1px;
    classDef yellow fill:#ffeb3b,color:#000,stroke:#333,stroke-width:1px;
    classDef green fill:#4caf50,color:#fff,stroke:#333,stroke-width:1px;
    classDef blue fill:#3f51b5,color:#fff,stroke:#333,stroke-width:1px;

```

