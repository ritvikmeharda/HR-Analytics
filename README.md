# HR Analytics

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Visualization](#data-visualization)
- [Findings and Insights](#findings-and-insights)
- [Recommendations](#recommendations)


### Project Overview

The primary objective of this data analysis project is to identify and analyze the key factors contributing to employee attrition within the company. By delving into the data and applying analytical techniques, we aim to uncover patterns, trends, and correlations that shed light on why employees leave the company. The insights gained from this analysis will inform strategic decision-making processes to mitigate attrition and improve employee retention.

### Data Source

Employee Data: The primary dataset used for this analysis is the "HR_Analytics.csv" file, containing comprehensive information about the employees of a company.

### Tools

- Microsoft Excel - Data Cleaning & Data Analysis
- Microsoft PowerBI - Creating Dashboard

### Data Cleaning and Preparation

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

- The attrition rate of 16% indicates a notable turnover within the company. This figure suggests a significant departure rate that warrants attention.
- Analysis reveals a direct correlation between attrition and employee salary, with 163 out of 237 departing employees earning salaries below 5000, notably lower than the company average.
- Age distribution among departing employees highlights a predominant representation from the younger and middle-aged groups, with the majority falling within the 26-35 age bracket.
- Tenure analysis indicates that a considerable portion of departing employees, particularly those with one year of tenure, are opting to leave the company.
- Job satisfaction ratings, measured on a scale of 1 to 4, indicate suboptimal satisfaction levels among employees, with over 40% rating their satisfaction between 1 and 2.
- The top job roles witnessing attrition include Laboratory Technicians, Sales Executives, Research Scientists, and Sales Representatives. These roles also correlate with lower-than-average salaries, potentially contributing to dissatisfaction and subsequent turnover.
- There exists a correlation between job roles, salary levels, and job satisfaction ratings, suggesting that employees in roles with lower salaries tend to report lower job satisfaction levels and are more likely to leave the company.

### Recommendations

1. Review and Adjust Compensation Packages:
   - Given the correlation between attrition and salary levels, it's crucial to review the company's compensation packages. Consider adjusting salary structures to ensure competitiveness and alignment with industry standards. Prioritize salary increases or bonuses for employees earning below-average salaries, particularly those in critical roles experiencing high attrition rates.
2. Enhance Employee Engagement and Support Programs:
   - Implement initiatives aimed at improving employee engagement and support. Develop mentorship programs, career development opportunities, and wellness initiatives to foster a positive work environment and enhance job satisfaction. Encourage open communication channels to address concerns and feedback effectively.
3. Retention Strategies for Younger Employees:
   - Given the significant representation of younger employees among those leaving the company, develop targeted retention strategies tailored to their needs and preferences. Provide opportunities for professional growth, skill development, and meaningful work assignments to enhance retention and career progression.
4. Improve Onboarding and Training Processes:
   - Enhance the onboarding process to ensure new employees receive comprehensive training, support, and resources from the outset. Implement mentorship programs or buddy systems to facilitate integration into the company culture and promote a sense of belonging.
5. Address Departmental Challenges:
   - Conduct a thorough review of departments experiencing high attrition rates, such as Laboratory Technicians, Sales, and Research roles. Identify underlying issues contributing to turnover, such as workload, leadership, or advancement opportunities, and implement targeted interventions to address these challenges.
6. Regular Feedback Mechanisms:
   - Establish regular feedback mechanisms, such as employee surveys or focus groups, to assess job satisfaction, identify areas for improvement, and track progress over time. Actively solicit employee input and involve them in decision-making processes to foster a culture of transparency and empowerment.
7. Monitor and Adjust Strategies:
   - Continuously monitor key metrics, including attrition rates, job satisfaction ratings, and employee feedback, to evaluate the effectiveness of implemented strategies. Adjust initiatives as needed based on evolving needs and feedback from employees to ensure ongoing improvement and alignment with organizational goals.

---
