# Power BI HR Attendance Analytics Dashboard

## 📌 Project Overview
This project analyzes **real-world employee attendance data** and converts **messy, unstructured monthly attendance sheets** into a **dynamic, automated Power BI dashboard**.

The solution automatically recalculates metrics for **each month**, providing insights into **presence, work-from-home (WFH), and sick leave (SL) trends** with minimal manual effort.

<img width="1169" height="665" alt="image" src="https://github.com/user-attachments/assets/d4182777-7a31-4750-af15-4bc306d6dcfa" />

---

## 📸 Dashboard Preview – Presence Insights
The dashboard presents a centralized **Presence Insights** view that includes:

- Overall **Presence %**
- **WFH %** and **Sick Leave %**
- **Total Working Days**
- Month-wise analysis using dynamic slicers
- Day-of-week based attendance patterns
- Individual employee attendance breakdown

---

## 🗂️ Data Source
- Real-world **Employee Attendance Excel sheet**
- Daily attendance records per employee across multiple months

---

## 🔄 Automated Data Transformation
Using **Power BI Power Query**, a fully automated data preparation process was built:

- Trigger-based functions to process **new monthly sheets automatically**
- Unpivoting wide attendance data into analytical format
- Standardizing attendance codes (P, WO, SL, etc.)
- Handling missing and inconsistent values
- Creating clean, reusable transformation logic

This ensures that adding a new month’s data **automatically refreshes all insights** without rewriting queries.

---

## 📊 Key Insights & Analysis Covered

### Organization-Level Metrics
- Total **Presence %**, **WFH %**, and **SL %**
- Total number of working days
- Daily trends for Presence, WFH, and SL

### Day-of-Week Analysis
- Identification of days with:
  - Highest employee presence
  - Highest absenteeism
  - Maximum WFH adoption
- Comparison of attendance behavior across weekdays

### Employee-Level Insights
- Attendance percentage per employee
- Breakdown of:
  - Office presence
  - WFH
  - Sick leave
- Comparative performance analysis across employees

---

## 🧮 DAX Measures & Calculations
Advanced **DAX** was used to create:

- Dynamic percentage calculations
- KPI measures for cards
- Time-based measures (daily, weekly, monthly)
- Conditional logic for thresholds and alerts

---

## 📈 Visualizations Used
The dashboard contains:

- KPI cards (Presence %, WFH %, SL %, Total Working Days)
- Line charts for daily trends
- Tables and matrix visuals for employee-level data
- Interactive slicers for month selection

---

## 🔔 Automation & Alerts
- Email alerts configured to notify stakeholders when **attendance falls below a defined threshold**
- Automated refresh for updated reporting

---

## 🔐 Sharing & Security
- Role-based access implemented
- Restricted views for employees
- Full dashboard visibility for founders and leadership
- Controlled report sharing and data security

---

## 🎯 Business Value
This project demonstrates how automated BI solutions can:

- Convert messy HR data into clean analytical models
- Reduce manual reporting effort
- Enable data-driven workforce decisions
- Provide scalable monthly HR analytics

---

## 🛠️ Tools & Technologies
- Power BI
- Power Query (M Language)
- DAX
- Microsoft Excel

---


## 📌 Conclusion
This end-to-end Power BI project highlights strong capabilities in **data transformation, automation, DAX modeling, visualization, alerting, and secure data sharing**, delivering a production-ready HR analytics dashboard.
