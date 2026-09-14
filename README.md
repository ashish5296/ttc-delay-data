# TTC Subway Delay Classification

An R-based machine-learning project that uses 2024 Toronto Transit Commission subway incident data to predict whether an incident will cause a delay of more than five minutes.

## Project Summary

The project analyzes approximately 25,000 TTC delay records and treats delay severity as a binary classification problem:

* **0:** Delay of five minutes or less
* **1:** Delay greater than five minutes

The goal was to clean the operational data, engineer useful features and compare classification models capable of identifying higher-impact incidents.

## Workflow

* Standardized inconsistent station and categorical records
* Handled missing values and outliers
* Engineered temporal and operational features
* Created the five-minute binary target
* Used upsampling to address class imbalance
* Split the data into 80% training and 20% testing sets
* Evaluated models using confusion matrices, accuracy and statistical measures

## Models Evaluated

* Logistic regression
* Stepwise regression
* Naive Bayes
* Recursive partitioning

## Results

Naive Bayes produced the strongest results in the completed analysis:

| Dataset  | Accuracy |
| -------- | -------: |
| Training |      71% |
| Testing  |      65% |

The results demonstrate both the potential and limitations of predicting subway-delay severity from incident records alone.

## Tools

**R · Data Cleaning · Feature Engineering · Upsampling · Statistical Modelling · Machine Learning**
