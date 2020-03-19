# ICU_Survival_Analysis_24hrs

## Business Use Case
- In clinical practice, estimates of mortality risk can be useful in triage and resource allocation
- It helps hospital to:
  - determine appropriate levels of care
  - prepare discussions with patients and their families around expected outcomes
- Also helps payers to know how the health outcomes of their policyholders will be affected, so that payers can identify useful policies

## Problem Statements
MIT's GOSSIS community initiative is seeking an efficient way to address the problems with existing severity of illness systems: 
- They often lack generalizability beyond the patients on whom the models were developed, and
- The models are often proprietary, costly to use (APACHE scoring system…), and suffer from opaque algorithms

## Objectives
Create a model that uses data from the first 24 hours of intensive care to predict patient survival with:
- Better prediction probability of death (as compared to apache_4a_icu_prob, apache_4a_hospital_prob)
- Minimize apache features 
- Transparent (easy to explain)
- Generalizability
- Less complexity


## Data
From MIT's GOSSIS community initiative 

Dataset of more than 90,000 hospital Intensive Care Unit (ICU) visits from patients, spanning a one-year timeframe. 
This data is part of a growing global effort and consortium spanning Argentina, Australia, New Zealand, Sri Lanka, Brazil, and more than 200 hospitals in the United States.

https://gossis.mit.edu/about/

WiDS Datathon 2020

https://www.kaggle.com/c/widsdatathon2020

## Model
- Logistic Regression
- Random Forest
- Light Gradient Boosting
- CatBoost
- Neural Network with PCA


