# Detecting Fraud In Health Care
Machine learning group project for DS 3000 to detect fraud by doctors using Python (Jupyter Notebook). 

## Summary

The topic of our project is detecting Medicare fraud. Many people abuse loopholes in health care to
funnel money to themselves, and we want to detect such patterns of fraud and counter it by using
data analysis.

Health care fraud costs the country much financially, especially with rising health care costs, but also
harms the patients who truly need it. By having a more efficient way to detect health care fraud,
more criminals will be stopped in their tracks. We may weed out corrupt physicians and also enforce
that the same cheat doesn’t happen.

Our large datasets include a total of around 200,000 rows and 55 unique feature variables such as
beneficiary information, whether or not they were diagnosed with a certain chronic condition, claims
and deductibles, and provider and physician data. The one outcome variable determines whether or
not a provider is potentially associated with fraud. Because we have so much data to work with, we
will only work with the inpatient data (30,000 rows) and inner join to narrow it down to just the
providers with a calculated target variable.

## Approach to the Problem
This was a categorization problem since the target variable is whether health care is detected or not. It is expected that only a small
percentage of the providers are associated with a ‘yes.’ In this way, our dataset is unbalanced in
terms of the target variable.

This code iterates through a Kaggle data set (the description for this dataset can be found in the excel file "Dataset Descriptions.xlsx").

## Analysis and Findings
After an analysis of the machine learning algorithms:    
 - k-Nearest Neighbor
 - Naive Bayes
 - Logistic Regression
 
 with and without feature selection and best parameters, k-Nearest Neightbors was found to be the most accurate.
 
Training set: 95.2%

Testing set: 87.7%




