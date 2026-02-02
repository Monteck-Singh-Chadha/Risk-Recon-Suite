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

────────────────────────────────────────────────────────────────────────────────

├── 📁 DIAGRAMS/
│   └── 🖼️ UseCase diagram.png
├── 📁 Proj Docs/
│   ├── 📁 BlackBooks/
│   │   ├── 📘 COMBINE BB.docx
│   │   ├── 📘 Combine First 5.docx
│   │   ├── 📘 Monteck BB.docx
│   │   ├── 📘 Monteck first5 BB.docx
│   │   ├── 📘 Pranay BB.docx
│   │   └── 📘 Pranay first5 BB.docx
│   ├── 🖼️ GANTT.png
│   ├── 🖼️ MVC architecture.png
│   ├── 🖼️ activity diagram.png
│   ├── 🖼️ seqquence dia.png
│   ├── 🖼️ state diagram.png
│   └── 📄 test cases.xlsx
├── 📁 core/
│   ├── 🐍 __init__.py
│   ├── 🐍 compliance_engine.py
│   ├── 🐍 engine.py
│   ├── 🐍 intelligence_engine.py
│   ├── 🐍 posture_engine.py
│   ├── 🐍 recommendation_engine.py
│   ├── 🐍 risk_engine.py
│   └── 🐍 scanner.py
├── 📁 data/
│   ├── 📁 history/
│   │   └── ⚙️ scan_history.json
│   ├── 📁 results/
│   │   ├── ⚙️ instagram.com_dns_tech.json
│   │   ├── ⚙️ instagram.com_risk_report.json
│   │   ├── ⚙️ instagram.com_vulnerabilities.json
│   │   ├── ⚙️ www.rkttechtrove.com_dns_tech.json
│   │   ├── ⚙️ www.rkttechtrove.com_risk_report.json
│   │   ├── ⚙️ www.rkttechtrove.com_vulnerabilities.json
│   │   ├── ⚙️ www.sonawanepranay05.wixstudio.io_directories.json
│   │   ├── ⚙️ www.sonawanepranay05.wixstudio.io_dns_tech.json
│   │   ├── ⚙️ www.sonawanepranay05.wixstudio.io_ports.json
│   │   ├── ⚙️ www.sonawanepranay05.wixstudio.io_risk_report.json
│   │   ├── ⚙️ www.sonawanepranay05.wixstudio.io_subdomains.json
│   │   ├── ⚙️ www.sonawanepranay05.wixstudio.io_vulnerabilities.json
│   │   ├── ⚙️ www.w3schools.com_directories.json
│   │   ├── ⚙️ www.w3schools.com_dns_tech.json
│   │   ├── ⚙️ www.w3schools.com_ports.json
│   │   ├── ⚙️ www.w3schools.com_risk_report.json
│   │   ├── 📕 www.w3schools.com_security_report.pdf
│   │   ├── ⚙️ www.w3schools.com_subdomains.json
│   │   └── ⚙️ www.w3schools.com_vulnerabilities.json
│   ├── 📁 users/
│   │   ├── 📁 174fb097-9228-49fa-898c-38ca8e855ec8/
│   │   │   ├── 📁 reports/
│   │   │   └── ⚙️ scan_history.json
│   │   ├── 📁 7f33eab1-a76f-4166-9a68-077bab2f1b67/
│   │   │   ├── 📁 reports/
│   │   │   └── ⚙️ scan_history.json
│   │   ├── 📁 8942d9ec-c82d-4f16-b713-4556a726de53/
│   │   │   ├── 📁 reports/
│   │   │   │   └── 📕 instagram.com_security_report.pdf
│   │   │   └── ⚙️ scan_history.json
│   │   ├── 📁 bba4fc10-0eda-4033-800e-32ac39322962/
│   │   │   ├── 📁 reports/
│   │   │   └── ⚙️ scan_history.json
│   │   ├── 📁 d1d61cdc-87fe-4f5b-925e-f70fd922411e/
│   │   │   ├── 📁 reports/
│   │   │   └── ⚙️ scan_history.json
│   │   ├── 📁 e104adb5-ee03-4b10-837d-839b268bc217/
│   │   │   ├── 📁 reports/
│   │   │   │   ├── 📕 www.rkttechtrove.com_security_report.pdf
│   │   │   │   ├── 📕 www.sonawanepranay05.wixstudio.io_security_report.pdf
│   │   │   │   └── 📕 www.w3schools.com_security_report.pdf
│   │   │   └── ⚙️ scan_history.json
│   │   ├── 📁 e2bcb77c-b0d9-4534-a529-bdd3d72a3bd7/
│   │   │   ├── 📁 reports/
│   │   │   │   ├── 📕 instagram.com_security_report.pdf
│   │   │   │   ├── 📕 www.rkttechtrove.com_security_report.pdf
│   │   │   │   ├── 📕 www.sonawanepranay05.wixstudio.io_security_report.pdf
│   │   │   │   └── 📕 www.w3schools.com_security_report.pdf
│   │   │   └── ⚙️ scan_history.json
│   │   ├── 📁 u001/
│   │   │   ├── 📁 reports/
│   │   │   └── ⚙️ scan_history.json
│   │   └── ⚙️ users.json
│   └── 📁 wordlists/
│       └── 📄 common_dirs.txt
├── 📁 modules/
│   ├── 🐍 __init__.py
│   ├── 🐍 dir_bruteforce.py
│   ├── 🐍 dns_fingerprint.py
│   ├── 🐍 port_scan.py
│   ├── 🐍 subdomain_enum.py
│   └── 🐍 vuln_scan.py
├── 📁 reports/
│   └── 🐍 report_generator.py
├── 📁 static/
│   ├── 🖼️ BG2.gif
│   ├── 🎨 auth.css
│   ├── 🖼️ bg.gif
│   ├── 🖼️ bg01.gif
│   └── 🎨 style.css
├── 📁 templates/
│   ├── 🌐 index.html
│   ├── 🌐 login.html
│   ├── 🌐 profile.html
│   ├── 🌐 result.html
│   └── 🌐 signup.html
├── 📁 utils/
│   ├── 🐍 __init__.py
│   ├── 🐍 helpers.py
│   └── 🐍 loggers.py
├── 📝 README.md
├── 🖼️ TEST1.png
├── 🐍 app.py
└── 📄 requirements.txt

────────────────────────────────────────────────────────────────────────────────

