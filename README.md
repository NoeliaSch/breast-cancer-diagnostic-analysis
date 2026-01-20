# Breast Cancer Diagnostic Analysis

## Objective:

-Exploratory data analysis
-Binary classification modeling
-Analytical SQL queries

## Dataset:

The Breast Cancer Wisconsin (Diagnostic) dataset was used for this project. It contains numerical features computed from digitized images of breast mass biopsies, along with a diagnostic label indicating benign or malignant cases.

## Project Structure:

The analysis follows a structured workflow:

 ### 1. Exploratory Data Analysis (EDA)
 
  -Inspection of feature distributions and variability
  -Identification of patterns and differences across diagnostic groups

 ### 2. Binary Classification Model
 
  - Logistic regression model built to predict diagnostic outcomes
  - Model evaluation using accuracy, precision, recall, F1-score, and ROC–AUC

 ### 3. SQL-Based Data Analysis
 
  - Creation of a SQLite database from the processed dataset
  - Analytical SQL queries to:
    - Count cases by diagnosis
    - Compute average feature values by diagnosis
    - Identify top-N records based on selected metrics

## Key Findings

-Malignant cases tend to show higher values in size-related features compared to benign cases.
-The classification model demonstrates strong predictive performance, with high accuracy and ROC–AUC.
-SQL aggregations and rankings reinforce consistent differences between diagnostic groups.

## Tools and Technologies

-Python (pandas, NumPy, scikit-learn)
-SQLite
-SQL (aggregation, grouping, ordering)
-Google Colab

## Notes

This project focuses on demonstrating data handling, analytical reasoning, SQL integration, and basic machine learning modeling, rather than clinical interpretation.


