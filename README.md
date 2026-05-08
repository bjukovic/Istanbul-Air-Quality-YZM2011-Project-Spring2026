# Istanbul Air Quality Prediction

## Problem Description
This project aims to predict whether daily air quality in Istanbul is unhealthy using environmental data. By combining air pollution indicators with weather conditions, the goal is to identify patterns associated with poor air quality. This problem has real-world importance, as it can help individuals and public authorities better understand and respond to harmful pollution levels.

## Dataset Source
The dataset used in this project was created by merging two publicly available datasets:

- Weather Dataset (Istanbul 2009–2019):  
  https://www.kaggle.com/datasets/vonline9/weather-istanbul-data-20092019/data

- Air Quality Dataset (Istanbul Historical Data):  
  https://www.kaggle.com/datasets/nitirajkulkarni/istanbul-tr-745044

The datasets were combined using a common date field to align daily weather conditions with air pollution measurements, creating a unified dataset tailored to this problem.

## Project Overview (P1, P2, P3)

This project follows a three-stage machine learning pipeline using the same dataset and real-world problem: understanding and predicting air quality in Istanbul.

- **P1 – Problem Formulation & Exploratory Data Analysis (EDA):**  
  In this stage, the weather and air quality datasets are merged, cleaned, and explored. The analysis focuses on understanding how environmental variables such as temperature, humidity, and wind relate to pollution levels. Key patterns, distributions, and data quality issues are identified.

- **P2 – Regression Modeling:**  
  In the second stage, regression models are used to predict continuous pollution levels (e.g., PM2.5) based on weather and environmental features. This helps quantify how different factors influence air pollution.

- **P3 – Classification & Model Evaluation:**  
  In the final stage, classification models are developed to predict whether air quality is unhealthy. The focus is on identifying high-risk days and evaluating model performance using appropriate metrics.

Together, these stages form a complete workflow, moving from understanding the data to predicting pollution levels and finally classifying unhealthy air conditions.

## Summary of Findings in P2

In Project 2, several regression models were developed to predict PM2.5 concentration levels in Istanbul using pollution and weather-related variables. Feature engineering techniques such as datetime decomposition, interaction terms, polynomial features, and log transforms were applied to improve model performance.

The results showed that models using multiple features performed better than the baseline model, indicating that air quality is influenced by a combination of environmental factors. Regularization techniques also helped reduce overfitting, with Lasso regression achieving the best overall performance and generalization ability.

