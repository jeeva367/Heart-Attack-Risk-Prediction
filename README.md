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




Airplane Price Prediction
Multiple Linear Regression | EDA | Power BI Dashboards
📌 Overview
This project predicts airplane market prices using multiple linear regression and explores the key technical, operational and economic factors influencing aircraft valuation—all visualised through interactive Power BI dashboards.
The dataset consists of 12,377 airplane records originally collected in Turkish, translated into English for analysis.

🎯 Objectives
Build a regression model to estimate airplane prices
Identify the most significant price-influencing factors
Perform EDA to uncover trends related to capacity, engine type, range, and pricing
Create interactive Power BI dashboards to visualise insights
Evaluate model performance using metrics: R², RMSE, MSE, MAE, Accuracy
📁 Dataset Features
Key features used in the modelling:

Model – Aircraft name/model
Production Year (1980 – 2023)
Number of Engines
Engine Type (Turbofan / Piston)
Capacity (max passenger seating)
Range (km)
Fuel Consumption (L/hr)
Maintenance Cost (hourly expense)
Sales Region (continent or regional market)
Price ($) – Target variable
🔧 Data Preprocessing & EDA
Handled missing values and standardised column names
Categorical encoding of variables (Engine Type, Sales Region)
Explored data via statistical summaries (summary(), str(), head() in R)
Visualised:
Price trends over production years
Fuel consumption by model
Passenger capacity distribution
Engine type impact on price
📊 Power BI Dashboard Highlights
Price comparison by aircraft model (average, minimum)
Maintenance cost vs price relationship
Fuel efficiency trends across models
Engine type distribution (91% Turbofan vs 9% Piston)
Regional sales insights
Yearly market price trends and forecast view
🤖 Model Performance
Metric	Value	Interpretation
R²	0.915	91.5% of price variance explained
RMSE	67,401,326	Moderate average error in USD
MAE	49,496,987	Average absolute error
Accuracy	75.25%	Good predictive performance, room for improvement
🔍 Key Insights
Engine type (Turbofan vs Piston), capacity and range are major drivers of price
Aircraft with turbofan engines and higher capacity consistently show higher market value
Maintenance cost is strongly correlated with older aircraft age
Sales region influences pricing trends based on market demand and region specific factors
🛠 Tech Stack
Language: R
ML: Multiple Linear Regression
Libraries: tidyverse, caret
Visualization & Dashboards: Power BI
Tools: GitHub, R Studio
🚀 Future Enhancements
Implement advanced models: Random Forest, XGBoost, Neural Networks
Deploy the model via Streamlit or Flask web application
Integrate external economic variables: fuel price trends, inflation rate
Build real-time prediction API with live data feed
✅ Conclusion
This project combines machine learning and interactive dashboards to analyse and forecast airplane prices. The insights and visualisations provide strategic value for aircraft manufacturers, buyers, leasing firms and aviation analysts.

⭐ If you found this repository useful, feel free to give it a star!
