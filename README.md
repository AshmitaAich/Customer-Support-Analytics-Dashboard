#  Customer Support Analytics Dashboard

**Author:** Ashmita Aich  
**Tools Used:** Tableau, Excel  
**Dataset Source:** [Kaggle](https://www.kaggle.com)

---

##  Project Overview

This project analyzes customer support ticket data to identify patterns in resolution time, SLA adherence, backlog volume and shift-wise performance.  
The goal is to uncover operational inefficiencies and support data-driven decisions in managing support resources and ticket prioritization.

---

##  Objectives

- Track overall ticket volume by shift and priority  
- Analyze SLA breach rates across ticket types  
- Measure and compare average resolution time by support shift  
- Monitor backlog of unresolved critical and high-priority tickets  
- Enable shift- and priority-level filtering for deeper insights  
- Visualize support performance KPIs in an interactive dashboard  

---

##  Data Cleaning (Excel)

- Removed irrelevant columns: `gender`, `age`, `email`  
- Renamed unclear or inconsistent column names for clarity  
- Created new calculated fields for analysis:
  - `Resolution Status` – based on whether the ticket was resolved  
  - `Resolution Time (hrs)` – duration between ticket creation and closure  
  - `SLA Breach Flag` – identifies tickets breaching SLA thresholds  
  - `Shift` – derived from ticket creation timestamp  
  - `Status Categorized` – grouped detailed status values into categories  

---

##  Dashboard Features (Tableau)

### ✅ KPI Cards
- Total Tickets  
- Average Resolution Time  
- SLA Breach Rate  
- Unresolved Critical Tickets  

###  Hourly Ticket Trend by Shift and Priority
Line chart showing ticket volume trends by hour, split by shift and priority. Reveals peak support hours and workload distribution.

###  Support Performance by Shift
Dual-axis chart comparing average resolution time and ticket count across Morning, Afternoon, and Night shifts.

###  SLA Compliance Rate by Channel
Bar chart comparing SLA adherence across support channels: Phone, Chat, Email.

###  Ticket Status Distribution by Priority
Clustered bar chart showing how ticket statuses (Open, Resolved, Pending) vary across priority levels.

###  Risk Analysis by Priority
Bar chart highlighting unresolved tickets at each priority level to assist in backlog cleanup.

###  Dynamic Filters
- Filter by Shift  
- Filter by Priority  

---

##  Key Insights

- **Afternoon shift** receives the highest ticket volume  
- **Night shift** has the longest average resolution time → potential staffing issue  
- **High-priority tickets** have an SLA breach rate of **8%**  
- Over **30%** of critical priority tickets remain unresolved  
- **Phone support** performs best in SLA compliance, with a **96%** rate  

---

##  Conclusion

The dashboard provides clear visibility into support operations, highlighting key issues like SLA breaches, delayed resolutions and unresolved high-priority tickets. These insights enable data-driven decisions to improve response efficiency, allocate resources better across shifts and enhance overall service quality.

---

## 🔗 Project Links

- ** Tableau Dashboard:**  
  [Customer Support Analytics Dashboard](https://public.tableau.com/views/CustomerSupportAnalyticsDashboard/CustomerSupportAnalyticsDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---
