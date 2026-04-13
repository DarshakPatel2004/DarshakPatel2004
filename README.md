# <div align="center">
#
# ```
#    ___   ___   ___    ___  _   _   _   _  _____  __   __
#   / __| / __| / _ \  | _ \| | | | | | | ||_   _| \ \ / /
#   \__ \| (__ | (_) | |  _/| |_| | | |_| |  | |    \   / 
#   |___/ \___| \___/  |_|   \___/   \___/   |_|     |_|  
# ```
#
# # **🔐 Darshak Patel**
# ## *Cybersecurity Engineer | Digital Forensics Researcher | ML/AI Security Specialist*
#
# [![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&width=700&lines=MSc+Digital+Forensics+%40+NFSU+Delhi;Cyber+Security+Specialist;Building+VulnForge+%28342K%2B+CVE+Intel%29;PhishScope+%28ML+Phishing+Detection+97%25%29;5%2B+OS+Digital+Forensics+Expert)](https://git.io/typing-svg)
#
# </div>

<div align="center">

**📍 Pune, Maharashtra, India** | **📧 darshakpatel2004@gmail.com** | **📱 +91-9823771052**

[GitHub](https://github.com/DarshakPatel2004) • [LinkedIn](https://linkedin.com/in/darshakpatel2004) • [Discord](https://discord.gg/darshakpatel.) • [Email](mailto:darshakpatel2004@gmail.com)

![Cisco CCST](https://img.shields.io/badge/Cisco_CCST-Cybersecurity-00B4E4?style=flat-square)
![NFSU](https://img.shields.io/badge/NFSU-MSc_Student-2C5282?style=flat-square)
![Cyber_First](https://img.shields.io/badge/Cyber_First-Internship_Completed-27AE60?style=flat-square)

</div>

---

## 📋 **Executive Overview**

<table>
<tr>
<td width="50%">

### 🎯 **Career Strategic Profile**
- **Education:** MSc Digital Forensics @ **NFSU Delhi** (2026)
- **Background:** BTech CSE @ **MIT ADT** (GPA: 7.39/10)
- **Certification:** Cisco CCST Cybersecurity
- **Domain:** Threat Intelligence & DFIR Automation
- **Status:** Final Year Researcher | Open for 2026 Roles

### 📊 **Operational Metrics**
- **PhishScope:** 97% Accuracy (186K+ Dataset)
- **VulnForge:** 342K+ CVEs (Automated Sync)
- **Investigations:** 10+ High-Impact Cases
- **Platform Expertise:** 5+ Operating Systems
- **Malware Research:** 20+ Types Categorized

</td>
<td width="50%">

### 🛠️ **Command Center**
```
╭─────────────────────────────╮
│ Threat Intelligence         │
│ • CVE aggregation           │
│ • Automated rule gen        │
│ • Risk ranking              │
└─────────────────────────────┘
┌─────────────────────────────┐
│ Machine Learning Security   │
│ • Phishing detection        │
│ • Anomaly detection         │
│ • Malware classification    │
└─────────────────────────────┘
┌─────────────────────────────┐
│ Digital Forensics           │
│ • Multi-OS analysis         │
│ • Evidence extraction      │
│ • Chain of custody         │
└─────────────────────────────┘
```

</td>
</tr>
</table>

---

## 💼 **Professional Experience**

### **🔍 Cyber Security Intern**
**Cyber First Private Limited | November 2024 - May 2025 | Pune, Maharashtra**

**Domain:** Digital Forensics & Cyber Incident Investigation

**Accomplishments:**
- ✅ Conducted **10+ critical forensic investigations** with comprehensive evidence analysis
- ✅ Expertise across **5+ diverse operating systems** (Windows, Linux, macOS, iOS, Android)
- ✅ Extracted & analyzed digital evidence from **10+ computers** & **10+ mobile devices**
- ✅ Applied advanced forensic techniques:
  - Memory dump analysis & RAM recovery
  - File system forensics & data carving
  - Mobile device extraction & analysis
  - Network traffic forensics
  - Malware triage & reverse engineering basics
  - Chain-of-custody documentation

**Tools & Technologies Used:**
```
┌─────────────────────────────────────────┐
│ Mobile Forensics Tools                  │
├─────────────────────────────────────────┤
│ • Cellebrite UFED → Device extraction   │
│ • Magnet Axiom → Multi-device analysis  │
│ • Oxygen Forensic Detective → Mobile    │
│ • Mobiledit Forensic Express → Analysis │
└─────────────────────────────────────────┘
┌─────────────────────────────────────────┐
│ Malware Analysis & Reverse Engineering  │
├─────────────────────────────────────────┤
│ • IDA Pro → Disassembly & debugging     │
│ • Ghidra → Binary analysis              │
│ • Burp Suite → Web vulnerability scan   │
└─────────────────────────────────────────┘
┌─────────────────────────────────────────┐
│ Network & SIEM Analysis                 │
├─────────────────────────────────────────┤
│ • Wireshark → Packet analysis           │
│ • NMap → Network reconnaissance         │
│ • Wazuh → SIEM & threat detection       │
└─────────────────────────────────────────┘
```

**Impact:**
- Directly contributed to 10+ ongoing investigation processes
- Demonstrated proficiency in multi-platform forensic analysis
- Built strong foundation for evidence handling & documentation

---

## 🚀 **Featured Projects**

### **1. VulnForge 🔥 — Automated Threat Intelligence Platform**

**Timeline:** April 2026 - Present | **Status:** Active Development

**Problem Solved:**
CVE management is fragmented across multiple sources and requires manual updates. VulnForge automates threat intelligence aggregation, correlation, and rule generation.

**System Architecture:**

```
┌──────────────────────────────────────────────────────────────────┐
│                     CVE SOURCE INTEGRATION                        │
├──────────────────────────────────────────────────────────────────┤
│                                                                  │
│  NVD (342K+ Records)  ──┐                                        │
│                         ├─→ Unified Data Ingestion ──┐           │
│  CISA KEV  ─────────────┤   & Deduplication         │           │
│                         ├─→                          ├─→ ┌────┐  │
│  AlienVault OTX  ───────┘                           │   │SYNC│  │
│                                                      └──→│ENG │  │
│                                                         └────┘  │
│                                                          ↓      │
│                                  ┌──────────────────────────┐  │
│                                  │  APScheduler            │  │
│                                  ├──────────────────────────┤  │
│                                  │ Daily Full: 02:00 UTC   │  │
│                                  │ Hourly Inc: Every hour  │  │
│                                  │ (Zero manual labor)      │  │
│                                  └──────────────────────────┘  │
└──────────────────────────────────────────────────────────────────┘
                                   ↓
┌──────────────────────────────────────────────────────────────────┐
│                  INTELLIGENCE PROCESSING                          │
├──────────────────────────────────────────────────────────────────┤
│                                                                  │
│  CVE Parsing  →  CPE String Linking  →  CVSS Scoring           │
│       ↓                ↓                     ↓                   │
│  Metadata Extraction → Asset Mapping → Risk Ranking             │
│                                                                  │
│  Output: Structured CVE Intelligence in SQLite Database         │
└──────────────────────────────────────────────────────────────────┘
                                   ↓
┌──────────────────────────────────────────────────────────────────┐
│              DETECTION RULE AUTO-GENERATION                      │
├──────────────────────────────────────────────────────────────────┤
│                                                                  │
│  Format 1: Snort/Suricata Rules    →  IDS Deployment           │
│  Format 2: Sigma SIEM Rules        →  SIEM Integration         │
│  Format 3: JSON Alert Templates    →  Custom Tools              │
│                                                                  │
│  Single-Click Export → Prod-Ready Rules                         │
└──────────────────────────────────────────────────────────────────┘
                                   ↓
┌──────────────────────────────────────────────────────────────────┐
│                    REAL-TIME DASHBOARD                           │
├──────────────────────────────────────────────────────────────────┤
│                                                                  │
│ • CVE Timeline View    • Asset Vulnerability Map               │
│ • Critical Alerts      • Trend Analysis                         │
│ • Rule Generation Log  • Export History                         │
└──────────────────────────────────────────────────────────────────┘
```

**Key Features:**

| Feature | Details |
|---------|---------|
| **Data Sources** | NVD, CISA KEV, AlienVault OTX (3 integrated feeds) |
| **Database Size** | 342,000+ CVE records aggregated |
| **Update Schedule** | Daily full sync @ 02:00 UTC + Hourly incremental |
| **Asset Tracking** | CPE-to-infrastructure mapping & auto-discovery |
| **Rule Generation** | 3 formats: Snort/Suricata, Sigma, JSON |
| **Deployment** | Single-click export, production-ready |

**Tech Stack:**
```
Backend:      Python • FastAPI • SQLite
Frontend:     React 18 • Vite
Scheduling:   APScheduler (for automated syncs)
Deployment:   Docker-ready architecture
Database:     Append-only SQLite design
```

**Metrics:**
- ⚡ **Zero manual updates** (fully automated)
- 📊 **342K+ CVEs** in unified database
- 🎯 **3 output formats** for multi-tool support
- 🔄 **2 sync schedules** for data freshness

---

### **2. PhishScope 🎯 — ML-Powered Phishing Detection Engine**

**Timeline:** January 2026 - Present | **Status:** Development + Deployment

**Problem Solved:**
Phishing URLs evade traditional regex-based detection. PhishScope uses engineered features and ensemble ML to achieve 97% accuracy on real-world datasets.

**Technical Architecture:**

```
PHISHING URL INPUT
       ↓
┌──────────────────────────────────────────┐
│  FEATURE ENGINEERING PIPELINE             │
├──────────────────────────────────────────┤
│                                          │
│ STRUCTURAL FEATURES (12 features):       │
│ • URL length & depth                    │
│ • Subdomain count & entropy             │
│ • Query parameter count                 │
│ • Fragment & scheme analysis            │
│ • Domain name structure                 │
│                                          │
│ LEXICAL FEATURES (8 features):          │
│ • Digit ratio & special char ratio     │
│ • Entropy & entropy variance            │
│ • Alphabetic character distribution     │
│ • Character set analysis                │
│                                          │
│ BRAND SIMILARITY (3+ features):         │
│ • Levenshtein distance scoring          │
│ • Known brand database matching         │
│ • TLD reputation scoring                │
│ • Homograph attack detection            │
│                                          │
│ Total: 20+ Engineered Features          │
└──────────────────────────────────────────┘
       ↓
┌──────────────────────────────────────────┐
│  TF-IDF VECTORIZATION                    │
├──────────────────────────────────────────┤
│ • Character n-gram analysis (2-grams)    │
│ • Term frequency weighting               │
│ • Feature normalization                  │
└──────────────────────────────────────────┘
       ↓
┌──────────────────────────────────────────┐
│  ENSEMBLE ML CLASSIFICATION               │
├──────────────────────────────────────────┤
│                                          │
│ Model 1: Logistic Regression            │
│ ├─ Probability: Phishing vs Legitimate  │
│ ├─ Confidence score                     │
│ └─ Fast inference                       │
│                                          │
│ Model 2: Random Forest (100 trees)      │
│ ├─ Feature importance ranking           │
│ ├─ Robust to outliers                   │
│ └─ Ensemble voting                      │
│                                          │
│ Model 3: XGBoost Gradient Booster       │
│ ├─ Gradient boosted decision trees      │
│ ├─ High precision tuning                │
│ └─ Best single model accuracy           │
│                                          │
│ VOTING STRATEGY:                        │
│ Hard voting (majority) for final output │
│                                          │
└──────────────────────────────────────────┘
       ↓
┌──────────────────────────────────────────┐
│  PREDICTION OUTPUT                       │
├──────────────────────────────────────────┤
│                                          │
│ Classification: Phishing OR Legitimate  │
│ Confidence Score: 0.0 - 1.0             │
│ Model Votes: (LR, RF, XGB)              │
│ Feature Importance: Top 5 features      │
│ Reasoning: Explainability               │
│                                          │
└──────────────────────────────────────────┘
```

**Performance Metrics:**

| Metric | Score |
|--------|-------|
| **Accuracy** | 97% ✓ |
| **Precision** | 0.97 (Low false positives) |
| **Recall** | 0.97 (Catches true cases) |
| **F1-Score** | 0.97 (Balanced performance) |
| **Training Data** | 186,230+ URLs |
| **Test Dataset** | Balanced phishing & legitimate URLs |

**User Interface & Deployment:**

```
┌─────────────────────────────────────────┐
│  STREAMLIT DASHBOARD                    │
├─────────────────────────────────────────┤
│                                         │
│ 📋 BATCH PROCESSING:                    │
│  • Upload CSV with URLs                 │
│  • Process 100+ URLs in seconds         │
│  • Export results to JSON               │
│                                         │
│ 🔍 SINGLE URL CLASSIFICATION:           │
│  • Real-time inference                  │
│  • Confidence visualization             │
│  • Model vote breakdown                 │
│                                         │
│ 📊 SOC CONTROL SIDEBAR:                 │
│  • Statistics & metrics                 │
│  • Historical data                      │
│  • Export options                       │
│                                         │
│ 💾 JSON EXPORT:                         │
│  • Structured output format             │
│  • Integration-ready                    │
│  • Timestamped results                  │
│                                         │
└─────────────────────────────────────────┘
```

**Tech Stack:**
```
ML Frameworks:  Scikit-learn • XGBoost • TensorFlow
Data Processing: Pandas • NumPy
NLP/Text:       NLTK • TF-IDF vectorization
Frontend:       Streamlit (interactive dashboard)
Data Format:    CSV input / JSON output
```

**Key Metrics:**
- 🎯 **97% Accuracy** on 186K+ URL dataset
- 📊 **20+ Features** engineered
- ⚡ **Real-time** inference (< 100ms per URL)
- 📈 **Ensemble approach** for robustness
- 💾 **Production-ready** API & dashboard

---

### **3. Malware Detection & Risk Ranking System**

**Timeline:** June 2024 - October 2024 | **Status:** Completed

**Objectives:**
Build an automated malware detection system with risk categorization for 1M+ files monthly.

**System Capabilities:**

```text
  [FILE INPUT (1M+ Monthly)]
           │
           ▼
┌── [DEEP LEARNING CLASSIFICATION] ──────────────────────────┐
│                                                            │
│ ◆ INFRASTRUCTURE (TensorFlow)                              │
│ ├─ Neural Network Architecture                             │
│ ├─ Multi-layer Feature Extraction                          │
│ ╰─ Real-time Triage Engine                                 │
│                                                            │
│ ◆ COVERAGE (20+ Types)                                     │
│ ├─ Ransomware/APT          ├─ Trojans/Backdoors            │
│ ├─ Botnets/Rootkits        ╰─ Cryptominers/Spyware         │
│                                                            │
└────────────────────────────┬───────────────────────────────┘
                             │
                             ▼
┌── [RISK RANKING ENGINE] ───┴─── [ALERT & DASHBOARD] ───────┐
│                                                            │
│  [SEVERITY LEVELS]         [INCIDENT RESPONSE]             │
│  ◆ CRITICAL (Ransomware)   ├─ Automated Alerting           │
│  ◆ HIGH     (Trojans)      ├─ Slack/Email Integration      │
│  ◆ MEDIUM   (Suspicious)   ├─ Timeline Analytics           │
│  ◆ INFO     (Benign)       ╰─ Executive Reporting          │
│                                                            │
└────────────────────────────────────────────────────────────┘
```

**Results Achieved:**
- 🔍 **96% Detection Accuracy** using predictive models
- ⚡ **40% Faster** threat identification vs baseline
- 📊 **1M+ Files** processed monthly
- 📈 **5-Category Risk** classification system
- 🎯 **20+ Malware Types** identified
- 🚨 **Automated Alerting** for incident response

---

## 🎓 **Education & Certifications**

### **👨‍🎓 MSc Digital Forensics & Information Security**
**National Forensics Science University, Delhi | Graduation: 2026**

**Specialized Coursework Completed:**
- **Unit V: Machine Learning & Deep Learning for Cybersecurity** ✅
  - Random Forest algorithms for classification
  - Isolation Forest for anomaly detection
  - LSTM networks for time-series threat detection
  - Convolutional Neural Networks (CNNs) for pattern recognition
  - Autoencoders for unsupervised learning
  - Comprehensive pseudocode documentation

**Core Competencies:**
- Network Security & Cryptography (AES, RSA, ECC)
- Digital Evidence Collection & Analysis
- SIEM Log Correlation & Threat Detection
- OWASP Top 10 Vulnerability Classes
- CVSS 3.1 Severity Scoring
- IT Act 2000 Legal Framework & Compliance
- Incident Response & Threat Hunting

---

### **🎓 Bachelor of Technology — Computer Science & Engineering**
**MIT ADT University, Pune | Graduation: 2025 | GPA: 7.39/10**

**Specialization:** Cyber Security and Forensics

**Key Subjects:**
- Penetration Testing & Vulnerability Assessment
- Cryptography & Network Security Fundamentals
- Ethical Hacking & Information Warfare
- Digital Forensics Fundamentals
- System & Network Administration
- Secure Software Development

---

### **🏆 Cisco Certified Support Technician (CCST) — Cybersecurity**
**Cisco | Certification Year: 2025** ✅

**Validates:**
- Network security fundamentals
- Threat identification & analysis
- Security tools & technologies
- Incident response basics
- Security best practices

---

## 💻 **Technical Skills Matrix**

### **Programming Languages**
| Language | Proficiency | Projects |
|----------|------------|----------|
| **Python** | Expert | VulnForge, PhishScope, ML projects |
| **JavaScript** | Advanced | React frontend development |
| **Bash** | Advanced | System administration, automation |
| **Java** | Intermediate | Algorithms, data structures |
| **C** | Intermediate | Low-level programming, systems |

### **Forensics & Investigation Tools**
| Tool | Use Case | Proficiency |
|------|----------|------------|
| **Cellebrite UFED** | Mobile device extraction | Expert |
| **Magnet Axiom** | Multi-device investigation | Expert |
| **Oxygen Forensic Detective** | Mobile analysis | Advanced |
| **Mobiledit Forensic Express** | Device forensics | Advanced |
| **IDA Pro** | Reverse engineering | Intermediate |
| **Ghidra** | Binary analysis | Intermediate |

### **Security & Pen Testing**
| Tool | Application | Level |
|------|-------------|-------|
| **Burp Suite** | Web vulnerability scanning | Advanced |
| **Wireshark** | Network packet analysis | Advanced |
| **NMap** | Network reconnaissance | Intermediate |
| **Wazuh** | SIEM & threat detection | Intermediate |

### **Machine Learning & AI**
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit-learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-000000?style=for-the-badge&logo=xgboost&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

### **Backend & Security Infrastructure**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

### **Frontend & Visualization**
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

---

## 📊 **GitHub Analytics & Contributions**

<div align="center">

[![Darshak's GitHub Stats](https://github-readme-stats.vercel.app/api?username=DarshakPatel2004&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&show_icons=true&icon_color=58a6ff&count_private=true&include_all_commits=true&line_height=27)](https://github.com/DarshakPatel2004)

[![GitHub Streak](https://streak-stats.demolab.com?user=DarshakPatel2004&theme=tokyonight&hide_border=true&background=0d1117)](https://git.io/streak-stats)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=DarshakPatel2004&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&layout=compact&langs_count=10)](https://github.com/DarshakPatel2004)

</div>

---

## 🏆 **Achievements & Recognition**

<div align="center">

[![GitHub Trophies](https://github-profile-trophy.vercel.app/?username=DarshakPatel2004&theme=tokyonight&no-frame=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&margin-w=3&margin-h=3&rank=SECRET,SSS,SS,S,AAA,AA,A,B)](https://github.com/DarshakPatel2004)

</div>

---

## 🎯 **Current Objectives (2026)**

### **💼 Career Trajectory**
- **MS in Cybersecurity:** Actively preparing for advanced studies in US/UK/EU (Fall 2026).
- **Security Research:** Seeking roles in Threat Intelligence, DFIR, or Security Automation.
- **Certifications:** Pursuing OSCP and GIAC specialized credentials.

### **🤝 Open for Collaboration**
- Developing open-source threat intelligence modules.
- Integrating ML into Digital Forensics workflows.
- Academic research on automated malware triage.

### **💬 Let's Discuss**
- Advanced threat detection & response
- Forensics workflow automation
- ML model selection for security
- Emerging security technologies
- Career development in cybersecurity

---

## 🌐 **Connect With Me**

<div align="center">

[![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/darshakpatel.)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/darshakpatel2004)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DarshakPatel2004)
[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/Darshak48502)
[![Reddit](https://img.shields.io/badge/Reddit-%23FF4500.svg?style=for-the-badge&logo=reddit&logoColor=white)](https://reddit.com/user/LocksmithSea713)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/diku_9603)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:darshakpatel2004@gmail.com)

</div>

---

<div align="center">

### **Let's Build Secure Systems Together! 🚀**

![Profile Views](https://komarev.com/ghpvc/?username=DarshakPatel2004&label=👁️+Profile+Views&color=58a6ff&style=flat-square)

**Made with ❤️ by a Cybersecurity Enthusiast**

*"Security is not a feature. It's a foundation for trust."*

**April 2026 | Driven by Curiosity & Innovation**

</div>
