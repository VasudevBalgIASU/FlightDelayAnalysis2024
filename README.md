## Overview
This project focuses on analyzing flight delays using advanced statistical and machine learning models. The goal is to uncover patterns, predict delays, and identify key contributing factors such as carrier inefficiencies, weather, and seasonal trends. By leveraging dataset from 2024, actionable insights are provided to enhance operational efficiency and reduce disruptions in airline operations.

## Key Features
- Exploratory data analysis to uncover seasonal and airport traffic trends.
- Hypothesis testing for delay causes and impacts.
- Machine learning models like Random Forest and K-Means clustering for delay prediction and classification.
- SHAP (SHapley Additive exPlanations) for explainable AI insights.
- Statistical validation through ANOVA, T-tests, and Chi-Square tests.

## Technologies Used
- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- SHAP

## Dataset Details
- **Source**: Bureau of Transportation Statistics and Kaggle.
- **Structure**: The dataset includes fields such as `arr_delay`, `carrier_delay`, `weather_delay`, and more.
- **Size**: Over 15,000 records for 2024 and additional data from 2018 for validation.
- **Preprocessing**: Handling missing values, feature scaling, and deriving new metrics like `is_delayed`.

## Visuals and Examples
- **Correlation Matrix**: Shows relationships between delay types.
- **SHAP Plots**: Highlights key features driving delay predictions.
- **Cluster Analysis**: Visualizes delay severity using K-Means.

## Results
- Key delay drivers identified: carrier delays and late aircraft delays.
- Random Forest achieved an accuracy of 99.98% for predicting delays.
- Actionable insights provided for minimizing delay impacts.

