# pottery-operations-analytics-through-powerbi-excel-v2 (Jira-Based Reporting)

This project represents Version 2 of the Pottery Operations Analytics solution, where the focus shifts from workflow design (V1) to **data-driven reporting, dashboarding, and business insights** using Excel and Power BI.

This version demonstrates my strength in:
- Data Analysis
- Dashboard Design
- Visualization
- Business Storytelling

---

## 📊 Project Overview

In Version 2, I built a complete analytics solution using **Jira-style task data**, focusing on:

- SLA tracking
- Task progress monitoring
- Team workload analysis
- Category-based issue analysis
- Executive-level dashboards

The goal was to transform operational data into **clear, actionable insights for leadership and non-technical stakeholders**.

---


---

# 📸 Dashboard Preview

## PowerBI Dashboard:
<img width="1311" height="724" alt="image" src="https://github.com/user-attachments/assets/ed0fde96-713e-4872-97c6-b74cdc9331df" />


## Excel Dashboard:
<img width="1511" height="799" alt="image" src="https://github.com/user-attachments/assets/c54708fa-9f4e-46e5-ab77-6889a5466a05" />

---

## 🧠 Business Objective

To help IT leadership answer:

- Where is most effort being spent?
- Which issues are recurring?
- Are we meeting SLA targets?
- Which teams are overloaded?
- How can efficiency be improved?

---

## 🛠️ Tools & Technologies

- Excel (Data Transformation & Cleaning)
- Power BI (Dashboard & Visualization)
- CSV (Jira Data Export)
- Pivot Tables (Initial Analysis)
- Data Modeling Concepts

---

## 🔄 Data Workflow (End-to-End)

1. Jira data exported in CSV format  
2. Data cleaned and transformed in Excel  
3. SLA logic and calculated fields created  
4. Data loaded into Power BI  
5. Interactive dashboards built for business users  

---

## 📌 Key Features of Dashboard

### 🔹 KPI Overview
- Total Tasks
- Completed Tasks
- In Progress Tasks
- Pending Tasks

---

### 🔹 SLA Health Analysis
- On Track vs At Risk
- SLA Breach Visualization
- Priority-based SLA performance

---

### 🔹 Ticket Analysis
- Ticket Count by Category
- Average Resolution Time by Category
- Identification of high-effort tasks

---

### 🔹 Team Workload Analysis
- Tickets handled per team
- Average resolution time per team
- Workload imbalance detection

---

### 🔹 Interactive Filters
- Assignee
- Priority
- Issue Key
- Category

---

## 📊 Key Insights

- Password Reset and Hardware Issues contribute to high ticket volume  
- Network Issues and Hardware Issues take longer resolution time  
- SLA breaches are more frequent in high-priority tasks  
- Certain teams (like IT Support / HR Systems) show higher workload  

---

## 💡 Business Recommendations

- Automate repetitive tasks (e.g., password resets)  
- Improve troubleshooting processes for complex issues  
- Prioritize high-SLA-risk tickets  
- Balance workload across teams  
- Build knowledge base for common issues  

---

## Project Explanation

### Situation
The objective was to analyze Jira-based operational data and present insights in a way that both technical and non-technical stakeholders could understand.

### Task
My responsibility was to transform raw Jira data into structured insights and create dashboards that highlight performance, inefficiencies, and improvement areas.

### Action
I extracted Jira data in CSV format, cleaned and transformed it using Excel, created SLA logic, and built interactive dashboards in Power BI to visualize key performance indicators and trends.

### Result
The final dashboard provided clear insights into ticket distribution, SLA performance, and team workload, enabling better decision-making and highlighting opportunities for automation and process improvement.

---

## 🧱 Repository Structure

pottery-operations-analytics-by-jira-v2/
│
├── README.md
├── data/
│ ├── raw/
│ │ └── jira_export.csv
│ └── processed/
│ └── cleaned_data.xlsx
│
├── dashboards/
│ ├── excel_dashboard.xlsx
│ └── powerbi_dashboard.pbix
│
├── docs/
│ └── screenshots/
│ ├── dashboard_overview.png
│ ├── sla_analysis.png
│ ├── workload_analysis.png
│
└── reports/
└── insights_summary.md
