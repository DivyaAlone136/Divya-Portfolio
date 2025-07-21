### 🏘️ **Project: Housing Market Data Analysis Using Power BI** (Datasource: Google Big Query)

**S**ituation:  
Understanding housing market dynamics is crucial for buyers, sellers, and investors. The goal was to analyze property listings to uncover pricing trends, renovation patterns, and location-based insights that influence real estate decisions.

**T**ask:  
Build an interactive Power BI dashboard that visualizes housing data across multiple dimensions—price, location, condition, renovation status, and property features. The report needed to support comparative analysis and highlight investment-worthy properties.

**A**ction:  
- **Data Preparation & Cleaning**  
  - Imported housing dataset from [Kaggle](https://www.kaggle.com/datasets) containing property details like price, bedrooms, bathrooms, sqft, condition, and renovation year  
  - Removed irrelevant columns (e.g., ID, view) and standardized categorical fields (e.g., condition, waterfront status)  
  - Created custom columns for:
    - **Renovation Status**: using conditional logic on `yr_renovated`  
    - **Property Age**: calculated from `yr_built`  
    - **Price per Sqft**: derived from price and living area  
    - **Condition Category**: mapped numeric values to descriptive labels (e.g., “Excellent”, “Fair”)  

- **Data Modeling & DAX**  
  - Built relationships between location, property features, and pricing tables  
  - Used DAX to calculate KPIs: average price by zip code, renovation impact, condition-based price variance  
  - Applied filters and slicers for dynamic analysis by city, condition, and renovation status  

- **Dashboard Design**  
  - Created visuals:  
    - Heat maps for price distribution by zip code  
    - Bar charts for condition vs. average price  
    - Line charts for year-wise pricing trends  
    - Pie charts for renovation status and property types  
  - Enabled drill-through pages for zip code-level insights  
  - Used Smart Narrative and tooltips for contextual storytelling
<img width="746" height="430" alt="Image" src="https://github.com/user-attachments/assets/cb5c1946-82c7-4c33-a4a3-998eb24612f8" />
<img width="753" height="440" alt="image" src="https://github.com/user-attachments/assets/23e3e058-5ac4-40d9-a0e6-329aadfac3c8" />
<img width="755" height="430" alt="image" src="https://github.com/user-attachments/assets/fa8b7d99-e6a5-4f07-9a5b-6b88a7551ec4" />

**R**esult:  
Delivered a comprehensive Power BI dashboard that revealed pricing hotspots, renovation impact on property value, and condition-based trends. The report empowered users to identify undervalued properties and make data-driven investment decisions. It showcased your ability to transform raw housing data into actionable insights using DAX, Power Query, and intuitive design.
