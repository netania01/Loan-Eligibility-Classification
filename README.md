
# Loan Eligibility Classification

This project aims to predict loan eligibility based on various attributes of a loan application using machine learning techniques. The dataset contains information about loan applicants, and the goal is to classify whether a loan application is eligible for approval or not. Two classification algorithms are used: **Logistic Regression** and **Decision Tree**.



## Dataset

`person_age`
`person_gender`
`person_education`
`person_income`
`person_emp_exp`
`person_home_ownership`
`loan_amnt`
`loan_intent`
`loan_int_rate`
`loan_percent_income`
`cb_person_cred_hist_length`
`credit_score`
`previous_loan_defaults_on_file`
`loan_status`


## Step

1. **Data Preprocessing**:
   - Handle missing values
   - Convert categorical variables into numerical format using encoding techniques
   - Normalize or standardize the numerical features, if necessary

2. **Model Training**:
   - Split the dataset into training and testing sets
   - Train the Logistic Regression model
   - Train the Decision Tree model

3. **Model Evaluation**:
   - Evaluate both models onfusion matrix and ROC curve



## Requirements
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

    