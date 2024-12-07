
# **VACCINE UPTAKE ANALYSIS**

## **INTRODUCTION**

## **Business Understanding**

### ***Problem Statement***
In this project, I am tackling a predictive modeling problem related to the uptake of the seasonal flu vaccine. Specifically,trying to predict whether individuals will take the seasonal flu vaccine based on various features (such as demographics, socioeconomic factors, and behaviors).

The business issue here is to improve the vaccination rates within a population by identifying individuals who are likely to get vaccinated (or not). This is especially important for healthcare organizations, insurance companies, or public health initiatives aiming to increase vaccination coverage to reduce the spread of seasonal flu. By understanding the factors that contribute to vaccine uptake, organizations can create targeted interventions that encourage more individuals to get vaccinated, thereby improving public health outcomes and reducing healthcare costs related to flu-related illnesses.

## **Main Objective**
The goal of this project is to develop a predictive model to estimate seasonal flu vaccine uptake

### ***Objectives***
This project aims to explore various factors influencing individuals' decisions to receive the seasonal flu vaccine. The following objectives are addressed:

1. **Socioeconomic Factors**  
   To examine the impact of socioeconomic factors on an individual's decision to receive the seasonal flu vaccine.

2. **Behavioral Factors**  
   To assess the role of behavioral factors in influencing an individual's choice to get the seasonal flu vaccine.

3. **Demographic Factors**  
   To investigate how demographic characteristics affect an individual's likelihood of receiving the seasonal flu vaccine.

4. **Knowledge, Perception, and Attitude**  
   To explore how an individual's understanding, views, and attitude towards the seasonal flu vaccine affect their decision to get vaccinated.


## **Data Understanding**

The datasets used in this project were obtained from Driven Data and originate from the National 2009 H1N1 Flu Survey (NHFS). These datasets provide comprehensive information on the social, economic, and demographic backgrounds of the survey respondents, along with their opinions on the H1N1 and seasonal flu vaccines. The data has been split into two parts: the training set features and the training set labels.

This dataset examines factors influencing the uptake of the **seasonal flu vaccine**, focusing on demographic, behavioral, and attitudinal variables.

## Key Insights:
1. **Vaccine Uptake**: The distribution is balanced with 12,435 vaccinated and 14,272 unvaccinated individuals.
2. **Demographics**: Older adults (65+), individuals with chronic diseases, and health workers show higher vaccine uptake. Education and income have weak correlations.
3. **Behavioral & Attitudinal Factors**: Preventive behaviors (mask-wearing, hand-washing) and positive vaccine opinions increase uptake.

## Key Findings:
- **Older individuals** and those with **chronic conditions** are more likely to be vaccinated.
- **Health workers** and individuals with **positive vaccine views** also show higher uptake.

## Model Evaluation Summary

### 1. Baseline Model
- **Accuracy**: 45.81%
- **Precision**: 45.81%
- **Recall**: 100%
- **F1-Score**: 62.84%
- **Insights**: The baseline model predicts the positive class (vaccine recipients) with high recall but poor precision, providing limited insights.

### 2. Logistic Regression
- **Accuracy**: 80.7%
- **Precision**: 80.6%
- **Recall**: 76.0%
- **F1-Score**: 78.3%
- **ROC AUC**: 0.876
- **Insights**: A strong performer with balanced precision and recall, and high ROC AUC, indicating good predictive power.

### 3. Decision Trees
- **Accuracy**: 77.5%
- **Precision**: 77.3%
- **Recall**: 72.0%
- **F1-Score**: 74.6%
- **ROC AUC**: 0.849
- **Insights**: Slightly lower accuracy and recall compared to Logistic Regression, but with good precision and a respectable ROC AUC.

### 4. Random Forest
- **Accuracy**: 80.1%
- **Precision**: 79.2%
- **Recall**: 76.8%
- **F1-Score**: 78.0%
- **ROC AUC**: 0.874
- **Insights**: Performs similarly to Logistic Regression, with slightly higher precision, and a competitive ROC AUC score.




