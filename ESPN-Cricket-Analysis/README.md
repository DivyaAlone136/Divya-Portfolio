### 🏏 **Project: ESPN Cricket Data Analysis Using Power BI**

**S**ituation:  
Cricket generates massive volumes of performance data across formats and tournaments. The goal was to analyze match and player statistics from ESPN Cricinfo to build an interactive dashboard that delivers insights into team strategies, player rankings, and match outcomes.

**T**ask:  
Design and implement a data analytics solution using Power BI to visualize cricket data scraped from ESPN Cricinfo. The dashboard needed to showcase batting and bowling metrics, match summaries, and dynamic filters for user-driven exploration.

**A**ction:  
- **Web Scraping & Data Collection**: Used Python (BeautifulSoup, Requests) to extract match, batting, and bowling data from ESPN Cricinfo. Saved datasets in CSV format for analysis.
- **Data Cleaning & Transformation**:  
  - Removed nulls, duplicates, and special characters (e.g., “(c)”, “†”)  
  - Standardized player names and match IDs  
  - Merged batting and bowling stats with match metadata  
- **Power BI Integration**:  
  - Imported cleaned data using Power Query  
  - Created relationships between tables for accurate modeling  
  - Built DAX measures for strike rate, batting average, bowling economy, and player rankings using `RANKX`  
- **Dashboard Design**:  
  - Developed interactive visuals: slicers by year, match type, and player  
  - Used conditional formatting and tooltips for enhanced UX  
  - Enabled drill-through pages for player-specific performance deep dives
  <img width="763" height="437" alt="Image" src="https://github.com/user-attachments/assets/0c119ce5-1073-4332-85a6-489b2a39f95c" />
  <img width="760" height="437" alt="Image" src="https://github.com/user-attachments/assets/6fd09833-95bb-401f-90f9-2b1a3a37a77f" />
  <img width="760" height="436" alt="Image" src="https://github.com/user-attachments/assets/cfe0f31a-2dce-4d17-af45-cc9a39a30302" />
**R**esult:  
Delivered a dynamic Power BI dashboard that allows users to explore cricket data across formats and years. The project helped identify top performers, analyze team strategies, and even simulate best playing XIs based on historical performance. It demonstrated end-to-end data analytics skills—from scraping and transformation to modeling and visualization.
