
## HR Attrition Report

This report presents an analysis of employee attrition based on the dataset provided. The analysis includes exploratory data analysis (EDA) and visualizations to identify trends and patterns related to employee turnover. The objective of this report is to understand the factors influencing attrition and provide insights for potential interventions to reduce turnover rates.

### 1. Data Overview
- The dataset consists of **1,470 records** with **35 features** related to employee demographics and job characteristics.
- Key features include:
  - Age
  - Attrition (Yes/No)
  - Business Travel
  - Daily Rate
  - Department
  - Distance from Home
  - Job Satisfaction
  - Monthly Income
  - Years at Company

### 2. Data Acquisition and Preprocessing
- The dataset was loaded using **Pandas**, and initial exploration revealed no missing values.
- Data types were checked to ensure proper handling of categorical and numerical variables.

### 3. Exploratory Data Analysis (EDA)
- **Descriptive Statistics:** Summary statistics were generated for numerical features, revealing insights into the distribution of attributes such as age, daily rate, and monthly income.
- **Attrition Rate:** The overall attrition rate was calculated, showing that approximately **16%** of employees left the company.

### 4. Visualizations
- **Distribution Plots:** Histograms were created to visualize the distribution of key numerical features such as Age and Monthly Income.
- **Attrition by Department:** Bar plots illustrated the attrition rates across different departments, highlighting which areas experienced higher turnover.
- **Correlation Heatmap:** A heatmap was generated to show correlations between numerical features, revealing significant relationships that may influence attrition.
- **Box Plots:** Box plots were used to compare Monthly Income distributions between employees who stayed and those who left, indicating potential salary disparities.

### Conclusion
The exploratory data analysis has provided valuable insights into employee attrition within the organization. Key findings suggest that factors such as job satisfaction, salary levels, and department affiliation significantly influence turnover rates. Further investigation into these areas could help develop targeted strategies to improve employee retention.

This report serves as a foundational analysis of the HR attrition dataset and can be expanded with additional modeling techniques to predict future attrition trends.


