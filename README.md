Customer Behavior Analysis & Business Decision Making
Project Overview

This project analyzes customer behavior using the Mall Customer Segmentation Dataset. The objective is to apply descriptive and inferential statistical techniques to understand customer demographics, spending patterns, and business insights that can help organizations make data-driven decisions.

The project simulates the work of a Data Analyst by exploring customer data, performing statistical analysis, visualizing trends, testing hypotheses, and deriving actionable business recommendations.

Objectives
Understand customer demographic and spending data.
Apply descriptive statistics to summarize data.
Visualize distributions and identify patterns.
Compare customer groups based on gender.
Analyze relationships between variables using correlation.
Perform hypothesis testing using a t-test.
Compute confidence intervals.
Generate business recommendations from statistical findings.
Dataset

Dataset: Mall Customer Segmentation Dataset

Features
Feature	Type	Description
CustomerID	Numerical	Unique customer identifier
Gender	Categorical	Male or Female
Age	Numerical	Customer age
Annual Income (k$)	Numerical	Annual income in thousand dollars
Spending Score (1-100)	Numerical	Score assigned based on spending behavior
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
SciPy
Project Structure
Section 1: Data Understanding
Load dataset
Examine shape and columns
Check missing values
Identify data types
Section 2: Descriptive Analysis

Calculate:

Mean
Median
Standard Deviation

for:

Age
Annual Income
Spending Score
Section 3: Data Visualization

Generate:

Histograms
Boxplots

Purpose:

Understand distributions
Detect skewness
Identify outliers
Section 4: Group Analysis

Compare male and female customers based on:

Average Annual Income
Average Spending Score

Visualization:

Bar Chart
Section 5: Correlation Analysis

Study relationships among:

Age
Annual Income
Spending Score

Visualization:

Correlation Heatmap
Section 6: Inferential Statistics

Perform Independent Two-Sample T-Test.

Hypothesis

Null Hypothesis (H₀):
Male and female customers spend equally.

Alternative Hypothesis (H₁):
Male and female customers spend differently.

Decision is made using:

p-value
Significance level = 0.05
Section 7: Confidence Interval

Calculate:

95% Confidence Interval

for the average customer spending score.

Section 8: Business Insights

Generate recommendations regarding:

Customer targeting
Market segmentation
Marketing strategies
High-value customer identification
Key Statistical Techniques Used
Descriptive Statistics
Data Visualization
Group Comparison
Correlation Analysis
Hypothesis Testing (T-Test)
Confidence Intervals
Expected Outcomes

By completing this project, students will be able to:

Interpret customer behavior using statistics.
Make evidence-based business decisions.
Understand practical applications of hypothesis testing.
Communicate analytical findings effectively.
How to Run
Install required libraries:
pip install pandas numpy matplotlib seaborn scipy
Place Mall_Customers.csv in the project directory.
Open the Jupyter Notebook:
jupyter notebook MINI_PROJECT_2.ipynb
Run all cells sequentially.
Conclusion

This project demonstrates how statistical analysis can transform raw customer data into meaningful business insights. Through descriptive statistics, visualizations, correlation analysis, hypothesis testing, and confidence intervals, organizations can better understand customer behavior and develop effective marketing and customer retention strategies.
