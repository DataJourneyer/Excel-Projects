# Bike Buyer Project

This project involves creating an interactive dashboard in Excel using a bike buyer dataset. The goal is to visualize various aspects of the data, such as income, gender, age, and commuting distance, and how these factors influence the purchase of bikes.

## Data Description
The dataset includes the following columns:
- **ID**: Unique identifier for each person.
- **Marital Status**: Married or Single.
- **Gender**: Male or Female.
- **Income**: Annual income.
- **Children**: Number of children.
- **Education**: Education level.
- **Occupation**: Job type.
- **Home Owner**: Yes or No.
- **Cars**: Number of cars owned.
- **Commute Distance**: Distance to work.
- **Region**: Geographic region.
- **Age**: Age of the person.
- **Purchased Bike**: Yes or No.

  ## Tools Used
- **Microsoft Excel**: Primary tool for data cleaning, analysis, and visualization.
  - **Pivot Tables**: Used for summarizing and analyzing data.
  - **Charts**: Created various charts for visual representation.
  - **Slicers**: Added for interactive filtering of data.
- **Excel Functions**: Utilized various functions like IF statements for data transformation.

## Steps and Procedures

### 1. Initial Setup
- Copy the raw data to a working sheet to preserve the original data.
- Remove duplicates from the dataset.

### 2. Data Cleaning
- Replace shorthand notations with full terms (e.g., "M" to "Male", "S" to "Single").
- Format the income column as currency.
- Standardize columns like "Home Owner" to "Yes" or "No".

### 3. Creating Age Brackets
- Add a new column for age brackets using nested IF statements:
  ```excel
  =IF(L2> 54; "Old"; IF(L2>=31; "Middle Age"; IF(L2<31;"Adolescent"; "Invalid")))

### 4. Building Pivot Tables
- Create pivot tables for different analyses:
- Average Income by Gender and Purchase Status: Shows the average income of individuals who did or did not buy a bike, segmented by gender.
- Commuting Distance Analysis: Examines how commuting distance affects bike purchases.

### 5. Creating Visualizations
 Use pivot tables to create charts:
- Average Income Chart: Displays average income by gender and purchase status.
- Commuting Distance Chart: Shows the distribution of commuting distances for bike buyers.

### 6. Formatting and Refinement
- Ensure charts are properly formatted, with clear titles, axis labels, and data labels.
- Adjust decimal places and add commas for better readability.

### 7. Dashboard Creation
- Combine pivot charts into a single dashboard.
- Use slicers for interactive filtering based on Marital Status, Region, and Education.

### Conclusion
This project demonstrates the process of data cleaning, preparation, and visualization using Excel. These insights can help businesses tailor their marketing strategies to target specific demographics more effectively. The slicers allow users to filter data by marital status, region, and education, providing a customizable view that can uncover specific trends within subgroups.

Some of the conclusions that can be made by this interactive dashboard:

- Income Disparities: Married individuals tend to have higher average incomes compared to single individuals, which could influence their likelihood of purchasing a bike.
- Age and Purchasing Patterns: The 31-54 age group shows the highest bike purchase rates, indicating a target demographic for bike sales.
- Commuting Distance: Individuals commuting longer distances are more likely to purchase bikes, suggesting a market segment focused on reducing travel time or cost.

