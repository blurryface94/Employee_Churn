# Employee Churn

Employee retention is very important as acquiring new employees can be quite expensive and time consuming. Therefore, understanding why employees leave is very important for the business to maximize efficiency and reduce training cost.

The objective of this analysis is to come up with best possible classification which could be used to predict if a certain employee is going to leave.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Data](#data)

## General info
### Reasons why employees quit:
* Worklife balance
* Bad managers/colleague
* Social pressure
* Better opportunities
* Personal reasons

### Objective
* To use pandas to load the Kaggle Employee Retention Analystics
* To explore and understand the dataset 
   * Viewing the data 
   * Profile leaving employees 
   * Correlation Analysis
* Department Analysis 
   * Leaving employees by department 
   * Analysis of Sales Department leaving
* To predict the retention of employees - Prediction analysis 
   * Support Vector Machine(SVM) 
   * Random Forest
   * Logistic Regression
* Comparing models and discuss improvements
* Challenges: 
  * Finding the optimum effective wage to prevent high rollers to not leave the company   
  * Comaparison with other companies job perks for an analysis of labour market offering   
  * Profiling employees for leadership succession/promotion
  
  ## Technologies
  The following technologies were used for this part of the project:
  * Python 3
  * Jupyter notebook
  * Pandas: Python package for data analysis
  * Matplotlib and Seaborn: Python 2D plotting library
  * Sklearn: Python package for modeling creation
  
   ## Data 
   The dataset was downloaded from Kaggle From Kaggle description:
   * satisfaction_level (0–1)
   * last_evaluation (Time since last evaluation in years)
   * number_projects (Number of projects completed while at work)
   * average_monthly_hours (Average monthly hours at workplace)
   * time_spend_company (Time spent at the company in years)
   * work_accident (Whether the employee had a workplace accident)
   * left (Whether the employee left the workplace or not (1 or 0))
   * promotion_last_5years (Whether the employee was promoted in the 9.last five years)
   * sales (Department in which they work for)
   * salary (Relative level of salary)
