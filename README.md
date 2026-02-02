# 🔐 RiskRecon Suite

**Automated Bug Bounty Recon & Risk Assessment Framework**

RiskRecon Suite is a web-based reconnaissance and risk assessment framework designed to streamline the initial stages of bug bounty hunting and ethical hacking. It automates information gathering, vulnerability analysis, and risk evaluation, helping security researchers reduce manual effort and work with structured, actionable insights.

---

## 🚀 Why RiskRecon Suite?

Reconnaissance is one of the most time-consuming phases in bug bounty workflows. Security researchers often rely on multiple tools, manual scans, and unstructured outputs. RiskRecon Suite solves this problem by providing:

- A centralized reconnaissance platform  
- Automated risk scoring and analysis  
- Clear compliance and remediation insights  
- Professional security reports  

All within an ethical, authorized, and user-friendly system.

---

## ✨ Key Features

- 🔑 Secure user authentication & session management  
- 🌐 Domain-based security scanning  
- ⚡ Simple Scan (fast assessment)  
- 🔍 Complex Scan (deep reconnaissance)  
- 🧠 Risk scoring & severity classification  
- 📋 OWASP compliance evaluation  
- 🛠️ Remediation recommendations  
- 📊 Security posture scoring  
- 👤 User-specific scan history  
- 📄 Downloadable PDF security reports  

---

## 🧠 Scan Modes

### 🟢 Simple Scan
- DNS & technology fingerprinting  
- Vulnerability detection  
- Risk score calculation  

### 🔴 Complex Scan
- All Simple Scan checks  
- Subdomain enumeration  
- Port scanning  
- Directory brute-forcing  

---

## 🧩 Tech Stack

- **Backend:** Python (Flask)  
- **Frontend:** HTML, CSS, JavaScript  
- **Security Tools:** Nmap, Subfinder  
- **Reporting:** ReportLab  
- **Storage:** JSON-based file storage  

---

## 📁 Project Structure
```text
RiskRecon-Suite/
│
├── app.py                     # Main Flask application entry point
│
├── core/                      # Core analysis & intelligence engines
│   ├── __init__.py
│   ├── risk_engine.py         # Risk score & severity calculation
│   ├── compliance_engine.py   # OWASP compliance evaluation
│   ├── recommendation_engine.py # Remediation recommendations
│   └── posture_engine.py      # Overall security posture scoring
│
├── modules/                   # Reconnaissance & scanning modules
│   ├── __init__.py
│   ├── dns_fingerprint.py     # DNS & technology fingerprinting
│   ├── subdomain_enum.py      # Subdomain enumeration
│   ├── port_scan.py           # Port scanning (Nmap integration)
│   ├── dir_bruteforce.py      # Directory brute-forcing
│   └── vuln_scan.py           # Vulnerability detection
│
├── reports/                   # Report generation
│   ├── __init__.py
│   └── report_generator.py    # PDF security report generation
│
├── templates/                 # HTML templates (Flask views)
│   ├── login.html             # User login page
│   ├── signup.html            # User registration page
│   ├── index.html             # Scan console (main workspace)
│   ├── profile.html           # User profile & scan history
│   └── result.html            # Scan results & analysis page
│
├── static/                    # Static assets
│   ├── css/
│   │   └── style.css          # Global cyber-themed styles
│   ├── images/
│   │   └── bg.gif             # UI background assets
│   └── js/
│       └── loader.js          # Client-side scripts
│
├── data/                      # Runtime data (ignored in Git)
│   ├── users/
│   │   └── .gitkeep
│   └── results/
│       └── .gitkeep
│
├── requirements.txt           # Python dependencies
├── .gitignore                 # Git ignore rules
├── LICENSE                    # Project license
└── README.md                  # Project documentation
