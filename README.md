
# Bike Sales Analysis

## Table of Contents
- [Project Overview](project_overview)
- [ Project Objective](project_objective)
- [Data Sources](data_sources)
- [Tools](tools)
- [Steps Followed](steps_followed)
- [Results/Findings](results_findings)
  
### Project Overview

This project is a full Excel data analysis and dashboard build based on a bike sales dataset. The work covers data cleaning,
transformation, pivot tables, visualization, and dashboard creation — all done step-by-step in Excel.The main goal is to create a complete Excel project including data cleaning, pivot tables, and an interactive dashboard.The dataset contains customer demographics and whether they purchased a bike.Lastly The final product should be a dashboard with visuals and filters that users can interact with

### Project Objective

To analyze a bike sales dataset and build a dynamic, interactive Excel dashboard that provides insights into customer demographics and purchasing behavior.

### Data Sources

Sales Data: This analysis is based on the "bike sales data.csv" file, which contains valuable information on customer demographics and buying patterns

### Tools 

   Microsoft Excel

        Functions: IF, nested IF, VALUE IF FALSE

        Features: Pivot Tables, Pivot Charts, Slicers, Formatting

### Steps Followed
 
1. 🧹 Data Cleaning

    Removed duplicates from the dataset.

    Standardized number formats (e.g., income set to currency).

    Reviewed and confirmed consistency in columns like Education, Occupation, Commute Distance.

    Fixed field naming issues (e.g., “m” and “s” replaced with “married” and “single” incorrectly — corrected to “Marital Status”).

2. 🧮 Data Transformation

    Created a new Age Bracket column using nested IF statements:

        Age < 31 → Adolescent

        Age 31–54 → Middle Age

        Age ≥ 55 → Old

3. 📌 Pivot Tables

Three pivot tables were built to analyze:

    Average Income by Gender and Bike Purchase

    Count of Bike Purchases by Commute Distance

    Bike Purchases by Age Bracket

    Some field labels like "10 miles" were renamed (e.g., “More than 10 miles”) to correct sorting issues in pivot views.

4. 📈 Charts and Visualizations

    Charts were created from pivot tables using Recommended Charts.

    Style elements were added:

        - Axis titles (e.g., Income, Gender)

        - Chart titles (e.g., Average Income per Purchase, Customer Commute, Age Bracket)

        - Decimal places and comma formatting were cleaned for readability.

<img width="1881" height="1102" alt="Picture1" src="https://github.com/user-attachments/assets/3abe8820-ae23-4ea7-81a3-08a2aeed2d3a" />
<img width="1652" height="993" alt="Picture2" src="https://github.com/user-attachments/assets/48bce451-71df-43de-a7ef-1bd7ed8a1930" />
<img width="1653" height="993" alt="Picture3" src="https://github.com/user-attachments/assets/3141ed9f-7cdf-4053-8d2f-34c345a16d2a" />



6. 📊 Dashboard Creation

    Moved visualizations to a new dashboard sheet.

    Removed Excel gridlines for a clean look.

    Created a Dashboard Header using "Merge & Center".

    Aligned charts using Shape Format > Align tools.

7. 🎛️ Interactivity with Slicers

    Added slicers for filtering visuals by:

        Marital Status

        Region

        Education

    Used Report Connections to link slicers to all pivot tables.

    Final dashboard allows filtering by demographics 

### Results/Findings

The analysis results are summarized as follows:

1. Middle-aged individuals (31–54) are the most likely to buy bikes.

2. Higher-income individuals are more likely to purchase.

3. Commute distance affects purchase behavior.

4. Married people earn more on average than single individuals in this dataset.

<img width="1451" height="775" alt="Screenshot Bike Sales Dashboard" src="https://github.com/user-attachments/assets/194fd856-9912-4c21-b508-6af90ebd6656" />


