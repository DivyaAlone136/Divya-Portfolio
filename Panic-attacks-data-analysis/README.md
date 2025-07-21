### 🧠 **Project: Panic Attacks Data Analysis Using Power BI**

**S**ituation:  
Mental health organizations and researchers often struggle to identify patterns in panic attack symptoms across demographics and lifestyle factors. The goal was to analyze anonymized patient data to uncover symptom prevalence, age-based trends, and behavioral correlations.

**T**ask:  
Design a Power BI dashboard that transforms raw health data into actionable insights. The report needed to highlight symptom frequency, age group segmentation, and lifestyle triggers—while remaining intuitive for non-technical users like NGO staff or healthcare volunteers.

**A**ction:  
- **Data Preparation & Transformation**  
  - Imported raw data from Excel or Snowflake into Power BI  
  - Cleaned nulls, duplicates, and standardized boolean fields (e.g., dizziness, chest pain)  
  - Created age group categories using DAX: Child, Adolescent, Adult, Senior  
  - Converted panic scores into categorical levels (Low, Medium, High)

- **Data Modeling**  
  - Built relationships between patient demographics, symptoms, and lifestyle factors  
  - Used DAX to calculate symptom prevalence (% of patients with dizziness, sweating, etc.)  
  - Applied `COUNTROWS`, `FILTER`, `DIVIDE`, `SWITCH`, and `IF` functions for dynamic KPIs

- **Dashboard Design**  
  - Created bar charts for symptom frequency and age group analysis  
  - Used line and area charts to correlate sleep hours, alcohol intake, and panic duration  
  - Designed small multiples to compare adolescents vs adults across triggers like PTSD, caffeine, and social anxiety  
  - Added slicers for gender, panic score, medical history, and trigger reasons  
  - Applied consistent color themes, tooltips, and Smart Narrative for storytelling

<img width="755" height="436" alt="Image" src="https://github.com/user-attachments/assets/ae4584a6-ef90-4184-80b3-42eae668c5e5" />

<img width="751" height="431" alt="Image" src="https://github.com/user-attachments/assets/054dd513-1173-47c9-ab32-ead7dce8b49a" />

<img width="746" height="430" alt="Image" src="https://github.com/user-attachments/assets/587e7eef-65d5-493e-8e50-8fbd3e8e9698" />

**R**esult:  
Delivered a dynamic Power BI dashboard that helped users explore panic attack patterns across age, symptoms, and lifestyle. The report empowered NGOs to tailor awareness campaigns based on triggers and demographics.
