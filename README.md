<div align="center">

# 👋 Hi, I'm Mojaki Tjeeka

### Computing graduate · Infrastructure · Security · Data & ML

*I build labs, break things on purpose, analyse what happened, and document it all.*

![Degree](https://img.shields.io/badge/BSc_(Hons)-Computing-0d1117?style=for-the-badge&logo=academia&logoColor=white)
![Security](https://img.shields.io/badge/Security-SOC_&_Blue_Team-e03c31?style=for-the-badge)
![Infra](https://img.shields.io/badge/Infrastructure-Virtualization_&_AD-0078D4?style=for-the-badge&logo=windows&logoColor=white)
![Data](https://img.shields.io/badge/Data-Analytics_&_ML-f7931e?style=for-the-badge&logo=python&logoColor=white)

</div>

---

## 🧭 About Me
I'm a BSc (Hons) Computing graduate with a background in Networking & Infrastructure Management, interested in building, supporting and securing IT environments.

My work focuses primarily on IT infrastructure and cybersecurity, with practical experience through hands-on labs involving Windows Server, Active Directory, VMware, Linux and Wazuh.

I learn by building realistic environments, testing them, troubleshooting failures and documenting the results.

- 🔭 Every project is a hands-on lab with configs, screenshots, and a formal write-up
- 🛡️ Blue team focus — I've gone deep on SIEM detection engineering, proactive threat hunting, and the full SOC analyst workflow from triage to post-incident report
- 💼 Open to **junior roles** in IT, security, data or software

---
## 🧠 What I Can Do

| 🛡️ Cybersecurity | 🖥️ Infrastructure | 💻 Dev & Automation | 📊 Data & ML |
|---|---|---|---|
| SIEM deployment & tuning | VMware lab environments | Python · PowerShell · Bash | Data cleaning & EDA |
| Windows event log analysis | Windows Server & AD DS | Git & GitHub workflows | Pandas · Matplotlib |
| Custom detection rule writing | DNS · DHCP · Group Policy | REST API integration | scikit-learn experiments |
| Threat hunting & IOC pivoting | Linux server administration | Scripting & automation | Jupyter notebooks |
| MITRE ATT&CK mapping | Network troubleshooting | Web apps (PHP · JS · Node) | Data visualisation |
| Incident response (NIST 800-61) | Virtualisation & snapshots | SQL & database management | Model evaluation |
---

## 🗂️ What I Work On

| | Area | What it covers |
|:-:|---|---|
| 🛡️ | **Security & Blue Team** | SIEM, detection engineering, threat hunting, incident response |
| 🖥️ | **Virtualization & Active Directory** | Lab design, domain services, networking, system administration |
| 📊 | **Data Analytics** | Cleaning, analysis, visualisation, dashboards |
| 🤖 | **Machine Learning** | Models, evaluation, applied experiments |
| 💻 | **Programming** | Scripts, tools, automation, small applications |

---

## ⭐ Featured Project: SOC Analyst Home Lab

> A defender-side SOC lab. Attacks run from Kali and are detected, hunted and responded to from the SIEM, with **no agent on the attacker machine**, mirroring real SOC visibility constraints.

[![soc-analyst-homelab](https://img.shields.io/badge/📂%20View%20the%20repo-soc--analyst--homelab-2ea44f?style=for-the-badge)](https://github.com/cyprianus-m-t/soc-analyst-homelab)

```
                 192.2.42.0/24  (VMware bridged)

   ┌──────────────┐        attacks         ┌─────────────────────┐
   │  Kali Linux  │ ─────────────────────▶ │ Windows Server 2012 │
   │  Attacker    │                        │ AD DS · DC          │
   └──────────────┘                        └──────────┬──────────┘
                                                      │ domain
                                           ┌──────────▼──────────┐
                                           │ Windows 11 Endpoint │
                                           └──────────┬──────────┘
                                                      │ agent logs
                                           ┌──────────▼──────────┐
                                           │  Ubuntu · Wazuh     │
                                           │  SIEM / XDR         │
                                           └─────────────────────┘
```

| | Project | Outcome | Skills |
|:-:|---|---|---|
| **01** | [SIEM Setup & Log Ingestion](https://github.com/cyprianus-m-t/soc-analyst-homelab/blob/main/project-1-siem-setup) | Deployed Wazuh, validated the end-to-end log pipeline, tuned audit policy | `SIEM` `Audit policy` |
| **02** | [Brute Force Detection](https://github.com/cyprianus-m-t/soc-analyst-homelab/blob/main/project-2-brute-force) | Simulated SMB/RDP attacks with Hydra; wrote custom frequency-correlation rules | `Custom rules` `MITRE ATT&CK` |
| **03** | [Active Directory Attack Detection](https://github.com/cyprianus-m-t/soc-analyst-homelab/blob/main/project-3-ad-attacks) | Detected rogue account creation, DA escalation, and log clearing via Windows event analysis | `AD security` `Log analysis` |
| **04** | [Threat Hunting](https://github.com/cyprianus-m-t/soc-analyst-homelab/blob/main/project-4-threat-hunting) | Reconstructed a 3-event attack chain from fragmented SIEM logs; wrote a P1 case note for Tier 2 escalation | `Hunting` `IOC pivoting` `Case documentation` |
| **05** | [Incident Response Simulation](https://github.com/cyprianus-m-t/soc-analyst-homelab/blob/main/project-5-incident-response) | Ran the full IR lifecycle — containment, eradication, recovery — and wrote the post-incident report | `NIST 800-61` `AD remediation` |

*"The attacker cleared the local Security log three times. Wazuh had already forwarded everything."*

---

## 🚀 Project Roadmap

Projects in progress or planned. I'll link each one here as it ships.

| Status | Area | Project |
|:-:|---|---|
| ✅ | 🛡️ Security | [SOC Analyst Home Lab](https://github.com/cyprianus-m-t/soc-analyst-homelab) |
| 🔨 | 🖥️ Infrastructure | Virtualization lab: hypervisor setup, networking, VM templates |
| 🔨 | 🖥️ Infrastructure | Active Directory lab: domain build, users and groups, GPO, DNS/DHCP |
| 📅 | 📊 Data | Data analytics project: dataset → cleaning → insights → dashboard |
| 📅 | 🤖 ML | Machine learning project: problem → model → evaluation → write-up |
| 📅 | 💻 | Programming projects: automation scripts and small tools |

<sub>✅ Done · 🔨 In progress · 📅 Planned</sub>

---

## 🔄 How I Work

```
  Plan  ─▶  Build  ─▶  Test / Break  ─▶  Analyse  ─▶  Document  ─▶  Improve
```

Every repo aims to include a clear README, setup steps, screenshots or outputs, and what I learned.

---

## 🧰 Toolkit

**🛡️ Security**

![Wazuh](https://img.shields.io/badge/Wazuh-005571?style=flat-square&logo=elastic&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE_ATT%26CK-e03c31?style=flat-square)
![NIST](https://img.shields.io/badge/NIST_SP_800--61-1f6feb?style=flat-square)
![Kali](https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-4682B4?style=flat-square)
![Hydra](https://img.shields.io/badge/Hydra-black?style=flat-square)

**🖥️ Infrastructure**

![VMware](https://img.shields.io/badge/VMware_Workstation-607078?style=flat-square&logo=vmware&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows_Server_2012-0078D4?style=flat-square&logo=windows&logoColor=white)
![Active Directory](https://img.shields.io/badge/Active_Directory-0078D4?style=flat-square&logo=microsoft&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu_Server-E95420?style=flat-square&logo=ubuntu&logoColor=white)

**📊 Data & 🤖 ML** 

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**💻 Programming**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

---

## 📫 Let's Connect

[![Email](https://img.shields.io/badge/Email-mojakitjeeka@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mojakitjeeka@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-cyprianus--m--t-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/cyprianus-m-t)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE)

<div align="center">

<sub>⚠️ All attack simulations run in an isolated lab environment.</sub>

</div>
