# Telco Customer Churn Analysis and Prediction

## Introduction

This project aims to predict customer churn in a telecommunications company by analyzing various customer attributes and behaviors. The dataset includes information such as customer demographics, services subscribed, contract details, and payment methods. The goal is to develop customer retention programs based on predictive modeling.

## Dataset

The dataset consists of 7043 rows and 21 columns, with the "Churn" column as the target variable indicating whether a customer has churned or not. Features include customer information, services subscribed, contract details, and payment methods.

[Dataset Source](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## Data Cleaning

Data cleaning steps were performed using Python and various libraries, including pandas, matplotlib, seaborn, and numpy. Notable steps include handling missing values in the "TotalCharges" column, converting categorical features into numerical format, and performing feature engineering to create new relevant columns.

## Feature Engineering

Several new features were created, such as "AverageCharges," "AboveAverageCharges," and "ServicesMost," to provide additional insights into customer behavior. Clustering using KMeans was also applied to create a new feature, "cluster," for potential model improvement.

## Data Analysis

Exploratory data analysis was conducted to understand the relationships between different features and customer churn. Conclusions and recommendations were drawn based on the analysis of contract types, numerical features, payment methods, and more.

## Modeling

XGBoost, a machine learning algorithm, was used for predictive modeling. The dataset was split into training and testing sets, and oversampling (ADASYN) was applied to address class imbalance. The model's performance was evaluated using classification reports and ROC-AUC scores.
