  Cyber Risk Assessment & Threat Intelligence Platform

 Project Overview:
This project is a **Cyber Risk Assessment & Threat Intelligence Platform** developed using Python. It integrates **network scanning**, **threat intelligence**, and **interactive visualization** into a single dashboard.

The system performs:
- Network scanning using Nmap
- Threat intelligence analysis using VirusTotal API
- Risk scoring and classification
- Visualization using charts and heatmaps
- Automated email alerts and PDF reports
- Historical scan tracking using a database

---

 Project Structure (Modular Design)


project/
│
|
├── modules/
|
│ ├── scanner.py # Handles Nmap scanning + VirusTotal API
|
│ ├── analyser.py # Risk scoring & severity classification
|
│ ├── db.py # SQLite database operations
|
│
├── dashboard/
|
│ ├── app.py # Main Streamlit dashboard
│ 
│
├── cyberscan.db # Database file
|
├── requirements.txt # Dependencies
|
└── README.md # Project documentation


---

##  Technologies Used

| Category | Tools |
|--------|------|
| Programming | Python |
| Scanning | Nmap |
| Threat Intelligence | VirusTotal API |
| Frontend | Streamlit |
| Visualization | Plotly |
| Database | SQLite |
| Email Alerts | SMTP (Gmail) |
| Environment | Google Colab |

---

## ⚙️ Modules Description

### 🔹 scanner.py
- Performs Nmap scans
- Parses scan results
- Integrates VirusTotal API

### 🔹 analyser.py
- Calculates risk scores
- Classifies severity (Low, Medium, High, Critical)

### 🔹 db.py
- Stores scan results
- Retrieves historical data

---

## 🚀 Features

- 🔍 Network scanning using Nmap  
- 🌐 Threat intelligence using VirusTotal  
- 📊 Interactive dashboard with charts  
- 🔥 Risk scoring & severity classification  
- 📈 Heatmaps, graphs, KPIs  
- 📄 PDF report generation  
- 📧 Email alerts (manual + auto)  
- 🗂️ Scan history tracking
  
---

## 📥 Installation & Setup

### Step 1: Install dependencies
pip install streamlit pandas plotly fpdf python-nmap
Step 2: Install Nmap
Windows: https://nmap.org/download.html
Linux:
sudo apt install nmap
🔐 Environment Setup (IMPORTANT)

Set these in your environment (Colab or local):

VT_API_KEY = "your_api_key"

GMAIL_SENDER = "your_email"

GMAIL_PASSWORD = "app_password"

GMAIL_RECIPIENT = "receiver_email"

▶️ How to Run
streamlit run dashboard/app.py
📊 Dashboard Features
Overview (KPIs + Charts)
Detailed Report
Scan History
Email Alerts

👉 Note:

Scan targets are defined in code (not user input)
No manual input for security reasons
🎯 Target Used for Scanning

Example:

scanme.nmap.org

This is a safe test target provided by Nmap.

📌 Agile Methodology

The project was developed using Agile:

Sprint-based development
Iterative feature integration
Continuous testing and debugging
👤 Team Members
Nikhitha Mondeddu

📈 Future Enhancements
AI-based anomaly detection
Real-time monitoring
Geo-IP attack visualization
Advanced reporting dashboard
✅ Conclusion

This project demonstrates a complete cybersecurity workflow by integrating scanning, analysis, visualization, and alerting into a single platform.

It provides actionable insights and helps in understanding network vulnerabilities effectively.
