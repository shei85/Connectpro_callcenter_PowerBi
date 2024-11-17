# **Performance Overview Dashboard**

## **Introduction**
This Power BI dashboard provides a focused view of company performance, specifically designed to monitor and track key performance indicators (KPIs) over time. 

Using a star schema model, the report integrates multiple data sources through the **Employee ID**, serving as the central key for analysis.

The report is built to address the need for real-time performance tracking, trend analysis, and KPI management, offering a clear and actionable visualization for decision-making.

---


## **Key Features**

### **KPIs Monitored**
- **Contacts per Hour:** Measure of team productivity.
- **Average Handle Time (AHT):** Time taken to manage tasks or calls.
- **% Calls Answered:** Proportion of answered calls relative to total.
- **Customer Satisfaction:** Reflecting feedback from customers.
- **Average Response Time:** Average time it takes to pick up a call after it is received.
- **Incidents per Hour:** Productivity metric focused on issue resolution.

### **Filters for Granularity**
The dashboard includes intuitive filters to allow users to drill down into specific timeframes and organizational segments:
- **Time-based filters:** Month, week, and day.
- **Organizational filters:** Department and supervisor.

### **Data Model**
- Built on a **star schema** for optimized performance.
- Central connection via the **Employee ID** across related tables.
- Includes a custom **calendar table** created with DAX to support time-based analysis (e.g., trends over months and weeks).

![image](https://github.com/user-attachments/assets/e615e92c-7de1-4e2b-acc3-d3e76ec84a9f)
---

## **Dashboard Layout**
### **Left Section: KPIs**
The left panel highlights the core KPIs currently being tracked by the company, offering a quick snapshot of performance metrics.

### **Top Section: Filters**
Filters are placed at the top for easy access, enabling dynamic data exploration by:
- Timeframe (month, week, day).
- Department and supervisor.

### **Center Section: KPI Table**
A detailed table presents the key indicators, grouped by department and month, allowing users to identify trends and performance variations at a glance.

### **Bottom Section: Visual Analysis**
- **Line Chart (Bottom Center):** Displays the trend of contacts per hour by month, offering insights into productivity patterns.
- **Pie Chart (Bottom Right):** Visualizes how work hours are distributed among activities such as:
  - Calls.
  - Back office tasks.
  - Other activities (e.g., training, breaks).

---

## **Media**
### **Images**
![image](https://github.com/user-attachments/assets/8e11dc02-53c0-4c4c-ae91-0a03017662a2)


### **Video**
A short video demonstrating the dashboard's functionality can be viewed 



https://github.com/user-attachments/assets/5969525d-174b-407f-964f-8ff2cafcb83c


---

## **Purpose**
This report addresses the critical need for tracking KPIs and understanding their evolution over time. By providing both high-level summaries and granular details, it equips managers and teams with actionable insights to drive performance improvements.
