# 🧠 KQL Query Repository

Welcome to the **Kusto Query Language (KQL)** repository. This is a centralized collection of reusable, production-ready KQL queries designed for cybersecurity, IT operations, compliance, and monitoring across the Microsoft ecosystem — including **Microsoft Sentinel**, **Microsoft Defender**, **Entra ID**, and **Azure Log Analytics**.

---

## 📌 Purpose

This repo is maintained to:

- 📊 Improve visibility across security and identity logs  
- 🛡️ Accelerate incident response and threat hunting  
- ⚙️ Automate reporting and compliance audits  
- 🧩 Serve as a modular library for dashboards, workbooks, and Logic Apps  

---

## 🗂️ Folder Structure

/KQL-Repo
│
├── SignInLogs/ # Sign-in tracking and geolocation-based queries
├── Defender/ # Queries for endpoint, cloud, and identity alerts
├── EntraID/ # Identity and access tracking
├── SentinelAlerts/ # Detection, automation, and alert rules
├── Workbooks/ # Queries powering Azure Monitor Workbooks
├── Examples/ # Sample outputs and usage in Power BI or Logic Apps
└── README.md # This file


---

## ⚡ Example Use Cases

| Use Case                       | Description                                                       |
|--------------------------------|-------------------------------------------------------------------|
| **Geo-Based Sign-In Review**   | Count sign-ins by IP, city, state, and country                    |
| **MFA Bypass Detection**       | Identify sign-ins missing MFA or showing failed attempts          |
| **Device Risk Audit**          | Track devices with high-risk signals from Defender                |
| **Suspicious Mail Rules**      | Detect auto-forwarding or manipulation of inbox rules             |
| **Inactive Users**             | List users with no interactive sign-ins in the last 90+ days      |

---

## 🚀 Getting Started

1. Open Microsoft Sentinel or Azure Log Analytics Workspace  
2. Copy the query from the appropriate `.kql` file  
3. Paste it into the **Logs (KQL)** blade  
4. Modify any filters (`Identity`, `AppDisplayName`, `TimeGenerated`) as needed  
5. Run the query and optionally export results or pin to workbooks  

