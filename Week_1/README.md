# Week 1 Task 1: User Behavior Data Analysis

## Overview
This task involves exploring and analyzing a User Behavior Dataset. The notebook demonstrates basic data manipulation, cleaning, and visualization using Python libraries like `pandas`, `matplotlib`, and `seaborn`.

## Files Included
- `Week_1_Task_1_Anosh.ipynb`: The Jupyter Notebook containing the code for data analysis and visualization.
- `user_behavior_dataset.csv`: The dataset used for this analysis.

## Key Steps Performed
1. **Data Loading:** Read the CSV dataset into a Pandas DataFrame.
2. **Data Cleaning:** Handled missing values, ensured proper data types (e.g., converting ID columns to string), and removed duplicate entries.
3. **Summary Statistics:** Generated statistical summaries to understand the central tendencies and spread of the data.
4. **Data Visualization:** Created various plots to understand data distributions and relationships:
   - Distribution histograms for numerical variables
   - Correlation heatmaps to identify relationships between numerical features
   - Boxplots for group comparisons (e.g., numerical variables by categorical variables)
   - Scatterplots to observe relationships between two numerical variables
   - Countplots to show the distribution of categorical variables

## Key Insights
1. **Correlation Patterns:** The heatmap reveals strong relationships between specific usage metrics, suggesting that heavy users in one area tend to be active across others.
2. **Group Variances:** The boxplot analysis shows significant differences in behavior across different user categories (e.g., Device Type or OS), indicating targeted optimization opportunities.
3. **Distribution Skewness:** The histograms show that most users fall within a specific activity range, with a small number of 'power users' representing outliers in the data.
