# Electric-Vehicle-Data-Analysis-KPI-Dashboard-Tableau-Business-Intelligence-Project
Electric Vehicle Data Analysis Dashboard using Tableau to track EV growth trends, state-wise adoption, BEV vs PHEV comparison, and key market insights through interactive visualizations.


##  Objective

To design and develop an interactive Tableau dashboard that analyzes Electric Vehicle (EV) population data based on geography, vehicle specifications, CAFV eligibility, and electric range.

The dashboard enables stakeholders, policymakers, and businesses to understand EV adoption trends, distribution patterns, and performance insights for data-driven decision-making.

## Tools Used

- Tableau Desktop / Tableau Public – Data visualization & dashboard creation  
- Microsoft Excel / CSV – Data source  
- Power Query (Optional) – Data cleaning and preprocessing  

## Dataset Overview

The dataset contains detailed information about registered Electric Vehicles, including:

- VIN (1-10)
- County
- City
- State
- Postal Code
- Model Year
- Make & Model
- Electric Vehicle Type
- Clean Alternative Fuel Vehicle (CAFV) Eligibility
- Electric Range
- Base MSRP
- Legislative District
- DOL Vehicle ID
- Vehicle Location
- Electric Utility
- 2020 Census Tract

## Key Performance Indicators (KPIs)

1. Total EV Registrations  
2. Total Battery Electric Vehicles (BEV)  
3. Total Plug-in Hybrid Electric Vehicles (PHEV)  
4. Average Electric Range  
5. Average Base MSRP  
6. Top 10 Cities by EV Count  
7. CAFV Eligible vs Non-Eligible Vehicles (%)  
8. Model Year Trend of EV Adoption  

## Dashboard Features

### EV Distribution by Geography
- Map visualization showing EV concentration by:
  - State  
  - County  
  - City  
- Drill-down functionality for detailed location analysis  

### EV Type Analysis
- Pie/Donut Chart:
  - Battery Electric Vehicle (BEV)
  - Plug-in Hybrid Electric Vehicle (PHEV)

### Make & Model Insights
- Bar Chart showing:
  - Top EV Manufacturers  
  - Most Popular Models  

### CAFV Eligibility Analysis
- Stacked bar showing:
  - CAFV Eligible
  - CAFV Not Eligible
  - Eligibility Unknown  

### Electric Range & Pricing Analysis
- Scatter Plot:
  - Electric Range vs Base MSRP  
- Identify high-range premium EVs  

### Year-wise Growth Trend
- Line Chart:
  - EV adoption trend by Model Year  

### Interactive Filters
- State  
- County  
- City  
- Model Year  
- Make  
- EV Type  
- CAFV Eligibility  

## Dashboard Configuration Details

### Data Cleaning
- Removed null VIN and duplicate records  
- Standardized city/state names  
- Converted Electric Range & MSRP to numeric format  
- Handled missing CAFV eligibility values  

### Data Modeling
- Created calculated fields:
  - Total EV Count  
  - BEV & PHEV classification  
  - Average Range  
  - Range Categories (Low / Medium / High)  
- Used geographic roles for mapping (State, County, Postal Code)  

### Design Principles
- Clean white background with green/blue EV theme  
- KPI cards at the top section  
- Charts arranged logically (Geography → Type → Performance → Trend)  
- Fully interactive with cross-filtering enabled  

## Insights Derived

- EV adoption is increasing significantly in recent model years.  
- Battery Electric Vehicles (BEVs) dominate over PHEVs.  
- Certain cities and counties show higher EV penetration.  
- Higher electric range vehicles generally have higher MSRP.  
- CAFV eligibility impacts adoption rates in specific districts.  

## Conclusion

The Electric Vehicle Population Data Dashboard provides a comprehensive and interactive overview of EV adoption trends, vehicle specifications, and geographic distribution.

This dashboard supports:
- Government policy evaluation  
- EV infrastructure planning  
- Market analysis for automobile manufacturers  
- Investment and sustainability decision-making  

By leveraging Tableau’s interactive capabilities, the project transforms raw EV registration data into meaningful, actionable insights.





















