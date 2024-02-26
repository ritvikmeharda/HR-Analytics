# HR Analytics

### Project Overview

The primary objective of this data analysis project is to identify and analyze the key factors contributing to employee attrition within the company. By delving into the data and applying analytical techniques, we aim to uncover patterns, trends, and correlations that shed light on why employees leave the company. The insights gained from this analysis will inform strategic decision-making processes to mitigate attrition and improve employee retention.

### Data Source

Employee Data: The primary dataset used for this analysis is the "HR_Analytics.csv" file, containing comprehensive information about the employees of a company.

### Tools

- Microsoft Excel - Data Cleaning & Data Analysis
- Microsoft PowerBI - Creating Dashboard

### Data Cleaning/Preparation

During the initial data preparation stage, several steps were undertaken to ensure the quality and integrity of the dataset:

1. Data Loading and Inspection: The dataset was loaded into the analysis environment, and an initial exploratory analysis was conducted to understand its structure, variables, and potential issues.
2. Handling Missing Values: Missing values were identified across the dataset, and appropriate strategies were employed to address them, ensuring minimal impact on subsequent analyses.
3. Removal of Redundant Columns: One column containing information on "Years with current manager" was removed due to its numerous null values and lack of relevance to the analysis objectives.
4. Duplicate Removal: Duplicate entries within the dataset were identified and removed to prevent bias and ensure accuracy in subsequent analyses.
5. Standardization of Categorical Values: Inconsistencies in categorical values were addressed, specifically instances where "Travel_Rarely" was inconsistently represented as "TravelRarely" in the "Business Travel" column. These were standardized to "Travel_Rarely" to maintain consistency and accuracy in the dataset.

### Exploratory Data Analysis

Exploratory Data Analysis (EDA) is a crucial step in understanding the underlying patterns and trends within the employee dataset. Through EDA, we aim to address key questions regarding attrition within the company and gain insights that can inform strategic decision-making and HR policies.

#### Key Questions:

1. Attrition Rate of the Company:
   - To assess the attrition rate, we calculated the proportion of employees who left the company during the observed period. This metric provides a foundational understanding of employee turnover and serves as a baseline for further analysis.
2. Salary Slab of Exiting Employees:
   - We analyzed the salary distribution of employees who left the company to identify any patterns or correlations between salary levels and attrition. This analysis helps in evaluating the impact of compensation on employee retention.
3. Age Group of Exiting Employees:
   - By examining the age distribution of departing employees, we aimed to understand if attrition is influenced by factors such as career stage or generational dynamics. This insight can guide targeted retention strategies tailored to different age groups.
4. Job Role Attrition:
   - We investigated attrition rates across different roles to identify areas with higher turnover. This analysis lets us pinpoint potential issues within specific job roles and design interventions to improve retention and morale.
5. Employee Tenure:
   - Analyzing the tenure of departing employees allowed us to assess factors such as career advancement opportunities, job satisfaction, and organizational culture's impact on retention. Understanding tenure patterns is essential for designing effective retention programs.
6. Job Satisfaction Rating:
   - We examined the job satisfaction ratings of employees to understand their satisfaction levels and how they correlate with attrition. This analysis provides insights into factors influencing employee morale and retention.

 
### Data Visualization

![HR_Analytics_Dashboard](https://github.com/ritvikmeharda/HR-Analytics/assets/95915956/f9fa0be3-eed2-48fb-adbc-7b089ad9a55f)

### Findings and Insights

- The Attrition Rate is 16% which is not optimal for a company.
- There is a direct correlation between Attrition and the Salary of the employees as more than 160 employees who left the company had a salary of less than five thousand which is less than the average salary of the company.
- The analysis shows that the employees leaving the company are mostly young and middle-aged, with most belonging to the age group 26-35.
- The analysis also shows that the employees leaving the company mostly work for 1 year and leave.
- The job satisfaction rating of the company is not good as more than 40% of employees rated their job satisfaction between 1 and 2.
- The analysis shows that the top four job roles from which the employees are leaving are Laboratory Technicians, Sales Executives, Research Scientists, and Sales Representatives.
- There is also a correlation between the job roles and salary of the employees as maximum employees in these roles have a salary of less than the average salary of the company. Also, there is a correlation between these metrics and job satisfaction rating as these employees having less salary in these roles have rated their satisfaction low. 










