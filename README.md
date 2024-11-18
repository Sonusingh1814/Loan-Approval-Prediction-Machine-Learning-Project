# Loan-Approval-Prediction-Machine-Learning-Project

#### This project aims to predict the approval status of loan applications using applicant data such as income, credit history, demographics, and loan details. It provides actionable insights to help financial institutions streamline their approval processes and reduce risks.

## Dataset

#### Loan_ID: Unique identifier for each loan application.
#### Applicant and Coapplicant Income: Income details of the applicant and coapplicant.
#### Loan Amount: Amount requested by the applicant.
#### Credit History: Indicates whether the applicant has a good credit history.
#### Property Area: Area where the property is located (Urban, Semi-Urban, Rural).
#### Loan_Status: Target variable indicating loan approval (Y/N).


## Project Workflow

 #### 1. Data Preprocessing:
##### Handled missing values and outliers.
##### Transformed and encoded categorical variables.
##### Created new features like combined income and logarithm transformations.

#### 2. Exploratory Data Analysis (EDA):
##### Visualized the distribution of key features.
##### Identified correlations with the target variable.

#### 3. Model Building and Evaluation:
##### Used classification models such as Logistic Regression and Decision Trees.
##### Evaluated performance using metrics like accuracy, precision, and recall.

## Technologies Used

#### Python - Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
#### Jupyter Notebook - For analysis and visualization

## Model Performance

#### Accuracy - Achieved high accuracy in predicting loan approvals.
#### Precision and Recall -  Balanced performance in identifying approved and rejected loans

## Key Insights

#### 1. Credit History is the strongest predictor of loan approval.
#### 2. Married applicants and those in semi-urban areas show higher approval rates.
#### 3. A balanced income-to-loan ratio improves the likelihood of approval.

## Conclusion

#### This project demonstrates how machine learning can effectively predict loan approval status and provide actionable insights for financial institutions. Further enhancements, such as incorporating additional features, can improve the model's accuracy and applicability.
