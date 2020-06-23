**AKI 1-Year Mortality Predictive Modeling**


This project aims to create a 1-year mortality predictive model for AKI(Acute Kidney Injury) patients using XGBoost, on a public database called MIMIC-III, which comprises of deidentified health-related data associated with over 40,000 patients who stayed in critical care units of the Beth Israel Deaconess Medical Center between 2001 and 2012.


The purpose of this project is to use existing patient's information to create a predictive model to predict the mortality of AKI (Acute Kidney Injury) patients, within a 1-year timeframe.


The workflow of this project is as follow:

-Create a comprehensive demographics of patients based on MIMIC-iii, including age of death, discharge, and ethnicitiy.

-Train a random forest classifier then utilizes gradient boosting through XGBoost

-Analyze accuracy using 10-fold cross validation



