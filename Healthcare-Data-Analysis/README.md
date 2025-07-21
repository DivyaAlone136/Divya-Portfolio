### 🏥 **Project: Healthcare Data Analysis Using Power BI & SQL Server (20M+ Records)**

**S**ituation:  
Healthcare organizations often struggle to extract actionable insights from massive clinical datasets. The challenge was to analyze over **20 million records** stored in SQL Server, covering patient demographics, hospital performance, infection rates, and clinical measurements.

**T**ask:  
Design an end-to-end data analytics solution that connects to SQL Server, profiles and transforms large healthcare datasets, and visualizes key metrics in Power BI. The dashboard needed to support hospital administrators in identifying trends, anomalies, and operational inefficiencies.

**A**ction:  
- **SQL Server Setup & Data Profiling**  
  - Connected to SQL Server using DirectQuery for real-time access  
  - Created views and stored procedures for efficient querying of large tables  
  - Implemented dynamic SQL for column-wise statistical profiling (median, mode, distribution)  
  - Used `PERCENTILE_CONT`, `GROUP BY`, and CTEs for statistical calculations  

- **Data Modeling in Power BI**  
  - Imported clinical tables: patient info, hospital records, infection logs, and temporal data  
  - Built relationships across hospital ID, admission dates, and diagnosis codes  
  - Applied DAX for KPIs: infection rate, average length of stay, readmission frequency  
  - Created calculated columns for age groups, severity levels, and treatment categories  

- **Dashboard Design**  
  - Page 1: Infection trends by hospital ID (line charts, heat maps)  
  - Page 2: Statistical insights (median, mode, distribution charts)  
  - Page 3: Hospital comparison (bar charts, slicers by region and specialty)  
  - Used Smart Narrative and tooltips for contextual storytelling  
  - Published to Power BI Service with scheduled refresh and role-based access
<img width="760" height="432" alt="image" src="https://github.com/user-attachments/assets/72287981-1068-4a4a-9bb5-ec8942d3aa7a" />
<img width="755" height="436" alt="image" src="https://github.com/user-attachments/assets/c4d997e2-260d-43b5-820c-fa8b4971a0c1" />

**R**esult:  
Delivered a scalable Power BI dashboard that visualized infection patterns, hospital performance, and clinical anomalies across millions of records. The solution enabled healthcare stakeholders to identify high-risk facilities, optimize resource allocation, and improve patient outcomes. It demonstrated your ability to handle **enterprise-scale data**, apply **advanced SQL techniques**, and build **insightful visualizations** under real-world constraints.
