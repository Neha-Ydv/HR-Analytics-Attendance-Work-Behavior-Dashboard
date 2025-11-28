# HR Analytics - Attendance & Work Behavior Dashboard  
*Strategic Insights for Workforce Optimization*

---

## Project Overview

This Power BI dashboard delivers an in-depth analysis of employee attendance patterns, enabling HR teams and business leaders to enhance workforce management and decision-making. By visualizing daily attendance records—including Presence %, Work From Home %, Sick Leave %, and more—the dashboard addresses key challenges in monitoring workforce engagement, optimizing resource allocation, and understanding leave behavior.

**Business Challenge Solved:**  
Accurate attendance analytics empower HR to identify trends, manage productivity, and formulate data-driven HR policies. With remote, sick, and medical leave insights, organizations can proactively address absenteeism and optimize working models.  

**Why Attendance Analytics?**  
- Improves employee utilization and engagement
- Detects absenteeism or burnout signals  
- Supports HR strategy and compliance  
- Enhances workforce planning

---

## Project Folder Structure

```
├── data/
│   └── Attendance_Daily.xlsx
├── dashboards/
│   └── HR_Attendance_Work_Behavior.pbix
├── images/
│   └── dashboard-preview.png
├── README.md
```
---

## Key Features

- **KPIs:** Presence %, WFH %, Sick Leave %, Medical Leave %, Total Employees
- **Trend Visuals:** Daily/Monthly line charts with trend lines
- **Performance Table:** Employee-wise attendance performance index
- **Attendance Matrix:** Cross-tab visualization of leave types and working days  
- **Interactive Slicers:** Filter insights by date, employee, month, and leave type  
- **Drill-through Capabilities:** Focus on individual and team-level analytics

---

## Dataset Description

- **Columns:**
  - `EmployeeID`, `EmployeeName`
  - `Date`
  - `Presence` (1/0)
  - `WFH` (1/0)
  - `SickLeave` (1/0)
  - `MedicalLeave` (1/0)
  - `OtherLeave` (type/category)
  - `TotalWorkingDays`
- **Time Period:** Typically covers 12 months of daily attendance data  

---

## Tools & Technologies Used

- **Power BI Desktop (.pbix)**
- Microsoft Excel  
- DAX (Data Analysis Expressions)  
- Power Query Editor  

---

## Dashboard Preview

<img width="1285" height="715" alt="dashboard" src="https://github.com/user-attachments/assets/9974d32f-49a1-47ad-b320-de1a245ed1ee" />

---

## Insights & Findings

- Highest presence rates observed in [months/teams]—indicating strong engagement.
- WFH utilization peaks during [timeframes/events].
- Sick and medical leave patterns reveal seasonal trends.
- Absenteeism clusters highlight risk periods for HR intervention.
- Certain employees consistently exhibit exceptional attendance performance.

---

## Business Impact / HR Impact

- **Actionable KPIs** for HR monthly reviews and leadership reporting
- Early identification of absenteeism and productivity bottlenecks
- Informed leave management and policy formulation
- Enhanced agility in workforce planning and remote work strategy

---

## What I Learned

- **Advanced Analytics:** DAX modeling, KPI calculation, dynamic visualizations  
- **Power BI Techniques:** Data transformation, interactive reporting, drill-through  
- **HR Domain Expertise:** Attendance metrics, workforce trends, strategic HR reporting

---

## Conclusion

This project demonstrates robust HR analytics, enabling strategic decisions and improved workforce management. Leveraging Power BI, it streamlines daily attendance analysis and empowers leadership with actionable insights.

---
