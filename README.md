❤️ Heart Attack Risk Prediction

📌 Project Overview

This project focuses on predicting heart attack risk using machine learning techniques based on patient demographic, lifestyle, and medical data. The goal is to identify high-risk individuals early and support preventive healthcare decisions through data-driven insights.

The project follows an end-to-end data analytics workflow, including data preprocessing, exploratory data analysis (EDA), machine learning model building, evaluation, and interactive dashboard creation.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------

🎯 Objectives

Identify key risk factors contributing to heart attacks

Build a reliable machine learning classification model

Visualize insights using Power BI dashboards

Enable early detection and preventive decision-making
----------------------------------------------------------------------------------------------------------------------------------------------------------------------

📊 Dataset Description

Records: 8,073

Features: 17

Target Variable: Heart Attack Risk (0 = No Risk, 1 = At Risk)

Key Features:

Age

Gender

Heart Rate

BMI

Blood Pressure

Cholesterol

Smoking Status

Alcohol Consumption

Physical Activity

Family History

Previous Heart Problems

Country & Continent
----------------------------------------------------------------------------------------------------------------------------------------------------------------------

🛠 Tools & Technologies Used

Programming: R

Data Analysis & EDA: R (ggplot2, dplyr)

Machine Learning: Random Forest Classifier

Model Evaluation: Accuracy, Confusion Matrix

Visualization: Power BI

Documentation: R Markdown

Version Control: Git & GitHub
----------------------------------------------------------------------------------------------------------------------------------------------------------------------

🔍 Exploratory Data Analysis (EDA)

Performed detailed EDA using:

Histograms (Age distribution)

Box plots (Cholesterol vs Risk)

Bar charts (Smoking, Physical Activity vs Risk)

Scatter plots (BMI vs Age)

Pie charts (Heart Attack Risk Distribution)

EDA helped uncover strong relationships between BMI, lifestyle habits, and heart attack risk.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------

🤖 Machine Learning Model

Algorithm Used: Random Forest Classifier

Train-Test Split: 80% Training / 20% Testing

Model Accuracy: 89.2%

The Random Forest model was chosen for its robustness, ability to handle mixed data types, and high predictive performance.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------

📈 Power BI Dashboard

An interactive Power BI dashboard was created to visualize:

BMI vs Heart Attack Risk

Physical Activity vs Risk

Alcohol Consumption vs Age

Country-wise Risk Distribution

Key KPIs (Average BMI, Physical Activity Days, BP Count)

The dashboard allows real-time filtering and improves interpretability for non-technical users.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------

🧠 Key Insights

Higher BMI and lower physical activity increase heart attack risk

Smoking and alcohol consumption significantly impact risk levels

Older age groups show higher vulnerability

Lifestyle changes can greatly reduce cardiovascular risk
----------------------------------------------------------------------------------------------------------------------------------------------------------------------

📂 Repository Structure
├── data/                  # Dataset (if shareable)
├── notebooks/             # R Markdown (.Rmd) files
├── dashboard/             # Power BI files
├── images/                # EDA & dashboard screenshots
├── README.md              # Project documentation
----------------------------------------------------------------------------------------------------------------------------------------------------------------------

🚀 Future Enhancements

Try advanced models (XGBoost, Neural Networks)

Feature importance visualization

Model deployment using Shiny or Flask

Include additional clinical biomarkers
----------------------------------------------------------------------------------------------------------------------------------------------------------------------

✅ Conclusion

This project successfully demonstrates the application of data analytics and machine learning techniques to predict heart attack risk using patient health and lifestyle data. By performing thorough data preprocessing, exploratory data analysis, and feature selection, meaningful patterns and key risk factors influencing heart attacks were identified
