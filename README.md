# Exploratory Data Analysis (EDA) Project on AMCAT Dataset

# Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on Amcat dataset containing employee details such as salary, education background, job performance, and personal traits. The main objective is to uncover trends and insights from the data that can assist in answering business questions such as salary distributions, factors influencing salary, and relationships between gender and job specializations.

# Objectives
- Data Preprocessing: Clean and prepare the data for analysis by handling missing values, formatting columns, and removing unnecessary data.
- Univariate Analysis: Explore the distribution of key variables, detect outliers, and visualize patterns in salary, job roles, and other columns.
- Bivariate Analysis: Investigate relationships between variables like salary and educational performance, and salary and job roles.
- Research Questions:
  1.Test the claim regarding fresh graduate salaries in specific job roles.
  2.Explore the relationship between gender and job specialization preferences.
- Conclusion: Provide key insights and actionable recommendations based on the analysis.
# Data Cleaning & Preprocessing
- Handled missing values by imputing the mean for the salary column.
- Converted date columns (DOJ, DOL, DOB) to a standard datetime format.
- Removed irrelevant columns and standardized categorical columns like Gender.
# Analysis Performed
1. Univariate Analysis
Histogram and Boxplot of the Salary column to observe distribution and detect outliers.
Count plots to analyze frequency distributions of categorical variables like JobCity and Gender.
2. Bivariate Analysis
Scatterplots and pairplots to explore relationships between salary and academic performance (e.g., 10th Grade Percentage, College CGPA).
Swarmplot and boxplots to examine salary variations across different job cities and roles.
Stacked bar charts to visualize the relationship between categorical variables (e.g., Gender and Job Specialization).
3. Research Questions

- Question 1: Tested a claim from a Times of India article about fresh graduate salaries, comparing it to the average salary for roles like Software Engineer, Programming Analyst, etc.
- Question 2: Analyzed the relationship between gender and specialization preferences to understand any observable trends.
# Key Insights
- Salary Distribution: The salary data showed skewness with some high outliers, indicating potential high earners.
- Influence of Education: Variables like the 10th percentage and College CGPA had a positive correlation with salary.
- Gender Preferences: There were noticeable trends in gender preferences for specific specializations and roles.
- Research Findings: The average salary of fresh graduates in programming-related roles aligned with the claim in the Times of India article.

# Conclusion
This EDA project provided valuable insights into salary distributions and factors influencing employee earnings. Gender and specialization preferences showed discernible patterns, and educational performance was found to be a significant factor in determining salary. These insights can help employers make data-driven decisions about salary and hiring.

# Tools and Libraries Used
Programming Language: Python
Libraries:
- pandas (for data manipulation)
- seaborn & matplotlib (for data visualization)
- numpy (for numerical operations)
