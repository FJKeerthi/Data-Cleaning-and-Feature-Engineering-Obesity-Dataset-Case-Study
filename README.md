# Data-Cleaning-and-Feature-Engineering-Obesity-Dataset-Case-Study

Dataset used : https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition

Obesity Data Analysis and Preprocessing for Machine Learning


This project focuses on analyzing, Visualization, preprocessing, and preparing an obesity dataset for machine learning tasks. The workflow includes data cleaning, feature engineering, outlier handling, and dataset splitting, all aimed at ensuring the data is ready for analytics and modeling.

**Project Objectives**

Preprocess the obesity dataset for machine learning readiness.

Perform feature engineering and transformation for analytical insights.

Split the dataset into training and testing sets for predictive modeling.

Ensure clean, structured, and analytics-ready data.

Dataset Description
The dataset contains various features related to obesity risk factors, such as:

Demographics: Gender, Age.

Physical Attributes: Height, Weight.

Lifestyle Habits: Smoking, Alcohol Consumption, Physical Activity.

Dietary Habits: Frequency of eating high-calorie foods, vegetable consumption, liquid intake.

Obesity Levels: Target variable categorized into various obesity levels.


**Tasks Performed**

1. Data Cleaning and Transformation
Gender: Encoded categorical values ("Female" → 0, "Male" → 1).
Age: Converted to integer type for numerical analysis.
Height and Weight: Rounded to two and one decimal places, respectively, for uniformity.

2. Feature Engineering
Renamed Columns: Renamed dataset columns for better readability and consistency.
Categorical Encoding:
Encoded lifestyle habits (e.g., Smoking, Alcohol Consumption) and other categorical features (e.g., Family History, Transportation Mode) into numerical values.
Consolidated obesity levels into fewer categories for better classification.

![image](https://github.com/user-attachments/assets/a3c089c8-2fc3-4366-b1f6-c9ee7aab00b7)


3. Data Visualization
Univariate Analysis:
Distribution plots for continuous variables (e.g., Age, Weight, Height).
Bar plots for categorical features (e.g., Smoking, Alcohol Consumption).
Multivariate Analysis:
Correlation heatmaps to visualize relationships between variables.
Pairplots to explore pairwise relationships among key features.
Class Distribution:
Visualized obesity level distributions using bar charts.

Examples
![image](https://github.com/user-attachments/assets/b4edd18a-674d-4a29-bdbd-bd7544cf0b8a)
![image](https://github.com/user-attachments/assets/81fe5e3a-dc9a-43cb-97f5-4d78eef3bd2a)
![image](https://github.com/user-attachments/assets/456a5f7f-d2d9-4e13-8e1b-bf517329a92f)


4. Dataset Splitting
Split the preprocessed dataset into training and testing sets (e.g., 80% training, 20% testing) for model development and evaluation.




