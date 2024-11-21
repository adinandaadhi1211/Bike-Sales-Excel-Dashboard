# Bike Sales Dashboard Project

This project involves creating an interactive dashboard using Microsoft Excel to analyze bike sales data. The dashboard provides insights into customer purchasing behavior based on various demographics and
preferences.

## Overview
The **Bike Sales Dashboard** project focuses on visualizing data related to bike purchases. It showcases key metrics like average income, customer commute distances, and age brackets of customers who purchased
bikes.

### Key Features:
- Filter-based exploration of customer data (e.g., marital status, region, education level).
- Dynamic pivot tables and charts for:
  - Average income per purchase by gender.
  - Purchase count by customer age brackets.
  - Commute distance and bike purchase correlation.

## Steps Performed
### 1. Data Cleaning
- **Duplicate Removal**: Identified and removed duplicate rows to ensure data integrity.
- **Column Value Updates**:
  - `Marital Status`: Updated "M" to "Married" and "S" to "Single."
  - `Gender`: Replaced "F" with "Female" and "M" with "Male."
- **Age Categorization**: 
  - Created a new column to classify customers into age brackets: 
    - **Adolescent**: Age < 20
    - **Middle Age**: Age 20-50
    - **Old**: Age > 50
    - Used an `IF` statement in Excel for these transformations.

### 2. Data Analysis
- **Age Bracket Analysis**: Examined bike purchases by different age groups.
- **Income Analysis**: Analyzed average income per purchase based on gender.
- **Commute Distance**: Explored the relationship between commute distance and bike purchase patterns.

### 3. Visualization
Created a dashboard using pivot tables and charts:
- **Bar Charts**: Displayed average income per purchase segmented by gender.
- **Line Charts**: Illustrated bike purchases across commute distances.
- **Combination Charts**: Showed the count of bike purchases by age brackets.

![Screenshot (168)](https://github.com/user-attachments/assets/85572284-c266-4c9d-8478-9eeb767fbeb9)


## Files Included

- **Bike Sales Dashboard.xlsx**: Contains the raw data, cleaned data, pivot tables, and final dashboard.
- **Screenshots**: Visual representation of the final dashboard.

## Insights Gained

- **Income Trends**: Males have slightly higher average income than females among bike purchasers.
- **Age Group Patterns**: Middle-aged customers are the dominant buyers of bikes.
- **Commute Impact**: Customers with shorter commute distances (0–5 miles) show higher purchase rates.

## How to Use
1. Download the **Bike Sales Dashboard.xlsx** file.
2. Open the file in Microsoft Excel.
3. Use slicers (filters) to explore the data dynamically:
   - Filter by marital status, region, or education level.
   - Analyze visual trends in income, commute, and purchase behavior.

## Tools Used
- **Microsoft Excel**:
  - Data cleaning and transformation.
  - Pivot tables and charts for dynamic data visualization.
    
## Future Scope

- Enhance the dashboard by adding conditional formatting for better insights.
- Automate the age categorization process using VBA or Power Query.
- Integrate external data sources for deeper analysis.
