# Harrison Vance
**Senior Technical Support Engineer | Production Incident Response**

[![Live Status](https://img.shields.io/badge/Status-All%20Systems%20Operational-brightgreen)](#) 

**2026 Focus:** Streamlining incident reproduction workflows, improving API observability, and eliminating the 12-hour "cold queue" for global SaaS platforms through reliable Follow-the-Sun (FTS) handoffs.

---

### About Me
I am a Technical Support & Operations professional with over 12 years of experience maintaining service stability in distributed systems. I specialize in the T2/T3 escalation layer: bridging the gap between customer-facing issues and core engineering teams. 

Based in **Bangkok, Thailand (UTC+7)**, I provide native-level English support for US and EMEA platforms during the APAC window, ensuring critical overnight escalations are diagnosed, triaged, and resolved before the US morning shift begins.

### My Support Philosophy
I believe that the best support engineers don't just close tickets; they protect engineering time by providing undeniable, reproducible evidence. My day-to-day focuses on:
* **Systematic Debugging:** I don't guess. I isolate variables across networks, APIs, and Linux environments to find the root cause.
* **Engineering Empathy:** I convert vague customer reports into structured bug tickets with clear reproduction steps, attached payloads, and isolated log traces.
* **Operational Toil Reduction:** If I have to do a diagnostic check more than three times, I write a Bash or Python script to automate it.

---

### Support Tooling & Diagnostic Narratives

*(Note: These are operational tools built to speed up incident triage and maintain system health)*

#### 1. [Ops-Diagnostics](https://github.com/h-vance/ops-diagnostics) (Python & Bash)
* **The Symptom:** Manual verification of production application services was slowing down initial ticket triage and increasing Mean Time to Resolution (MTTR). 
* **The Investigation:** Support teams needed a faster way to confirm if a reported outage was a localized user issue or a broader service degradation.
* **The Resolution:** Developed lightweight Python diagnostic scripts to automatically ping endpoints, parse health status, and monitor application log files for recurring error patterns. Reduced manual verification time and accelerated engineering escalations.

#### 2. [Log-Rotation-Maintenance](https://github.com/h-vance/log-rotation-maintenance) (Bash)
* **The Symptom:** Unmanaged production application logs risked filling server storage, potentially leading to service degradation and lost diagnostic data.
* **The Resolution:** Implemented automated Bash scripts for log rotation, compression, and cleanup on Linux servers. Ensured continuous availability of storage and preserved critical logs for post-incident RCA.

#### 3. [Cloud-Operations-Runbook](https://github.com/h-vance/cloud-operations-runbook)
* **The Impact:** Authored and maintained 15+ comprehensive technical SOPs. 
* **The Value:** Standardized common support tasks, reduced tribal knowledge, and improved the efficiency of the broader support team by providing repeatable troubleshooting paths.

---

### Technical Stack

* **OS & Infrastructure:** Linux CLI (Operational Troubleshooting), AWS (EC2, CloudWatch), GCP
* **API & Web Diagnostics:** REST API Triage, cURL, Postman, HTTP Payloads, SSL/TLS, DNS, TCP/IP
* **Scripting & Automation:** Python (Script Debugging), Bash
* **Workflows & Identity:** Jira, Zendesk, Incident Management, RCA, Okta, SAML, OAuth

**Contact:** [hvance788@gmail.com](mailto:hvance788@gmail.com) | [LinkedIn](https://linkedin.com/in/harrison-vance) | 
