
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

1. **Import Libraries**:
Essential libraries such as pandas, numpy, matplotlib, and machine learning frameworks.

2. **Import Dataset**:
Load and preprocess the dataset.

3. **Data Overview**:
- Understand the dataset, check for missing values, and explore feature distributions.
- Exploratory Data Analysis (EDA)
- Perform visualizations and statistical analysis to gain insights into the data.

4. **Machine Learning Model Development & Evaluation**:
- Train and classification models to predict loan eligibility with Regression model and Decision Tree.
- Evaluate both models onfusion matrix and ROC curve


## Requirements
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Instalation
To run this project, install the required dependencies:

`pip install pandas numpy matplotlib scikit-learn`

## Usage
Run the notebook to process the dataset and train the model:

`jupyter notebook Classification.ipynb`

## License
This project is open-source and available for further modifications and improvements.
