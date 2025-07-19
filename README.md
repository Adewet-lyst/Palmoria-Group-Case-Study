# Palmoria-Group-Case-Study
My second DSA Project

## Palmoria Group HR Analysis

### Project Overview
The Palmoria group is a manufacturing company based in Nigeria, is embroiled in issues bordering on gender inequality in its 3 regions. This data analysis project aims to focus on gender related issues within the organization and its regions.

### Data Source
The data source used here are 3 sets;
- The Palmoria Group employee data: This contains the employees details.
- The Bonus Mapping: This contains rules for making payments to the employees in the company and their work rating.
- The Bonus Rules: This contains the rukes for making payments to the employees in the company and their work rating.

### Tools Used
- Microsoft Excel
- Microsoft Power Bi
- Measures
- Modelling
- Tables

### Data cleaning and Preparation
- Microsoft Excel for Text Cleaning: In data cleaning and preparation the gender column contains male, female, and blank so i replaced the blank with undisclosed using replace values.
 - Department column: There are few cells that has "NULL" text, so i removed them by unchecking the list rows.
 - Salary Column: There are cells that has "NULL" text in the column, so it was removed by unchecking it from the list of salary rows.
- Microsoft Power Bi: To remove duplicates, i right click on the name column then click remove duplicate.
 - I unpivot other columns in the Bonus rule table, then change Attribute to Rating and Values to Bonus %
 - Merge Query was used to extract Bonus % column from Bonus rule table to Employees table.
 - Custom column was used to create a new column to calculate Bonus Amount, New salary and Salary Band.
- Measures: New measures are created to calculate; Average rating by gender, Rating count by gender, Average salary by gender and employees below minimum salary.
- Model is used to create many to many relationship between the three tables.
- Table is used to analyse the total salary bylocation and gender

### Exploratory Data Analysis
- What is the gender distribution in the organization? Distil to regions and department.
- Show insight on rating based on gender.
- Analyse the company's salary structure. Identify if there is a gender pay gap. If there is, identify the department and regions that should be the focus of management.
- A recent regulation was adopted which requires manufacturing companies to pay employees a minimum of $90,000.
  - Does Palmoria meet this requirement'
- Show the pay distribution of employees grouped by a band of $10,000. For examples,
  - How many employees fall into a band of $10,000 - $20,000, $20,000 - $30,000, etc
- Also visualize this by region

### Data Analysis/Findings
- There is gender pay gap across all regions of the compay.
- Male employees earned more in nine departments across the company.
- Higher bonus was accrued to female employees in the period of review.
  
### Conclusion/Recommendation
- Palmoria group should review its employement and renumeration policy to prevent gender disparity.
- The company is advice to review its salary structure across the company to meet the minimum wage requirement.
