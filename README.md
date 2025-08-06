# Diabetes Analysis 


## NON-TECHNICAL EXPLANATION OF YOUR PROJECT
This project contains an analysis of surveis from more than 200k patients asking about their physical and mental conditions to determine if they have risk of develope Diabetes.

## DATA
Data sources https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators

**For what purpose was the dataset created?**
To better understand the relationship between  lifestyle and diabetes in the US

**Who funded the creation of the dataset?**
The CDC

**What do the instances in this dataset represent?**
Each row represents a person participating in this study.

**Are there recommended data splits?**
Cross validation or a fixed train-test split could be used.

**Does the dataset contain data that might be considered sensitive in any way?**
- Gender
- Income
- Education level

**Was there any data preprocessing performed?**
Bucketing of age

**Additional Information**
Dataset link: https://www.cdc.gov/brfss/annual_data/annual_2014.html

**Has Missing Values?**
No

## MODEL 
Because this is a classification problem three models were considered.
- K-nearest neighbors
- Rigde regression
- Decision trees

## HYPERPARAMETER OPTIMSATION
Different techiniques were studied:
- Grid Search selection for K-nearest neighbors.


## (OPTIONAL: CONTACT DETAILS)
e-mail: jcrm86@gmail.com