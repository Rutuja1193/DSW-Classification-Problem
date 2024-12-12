# Classification problem for Loan Default Prediction

This project aims to predict loan approval statuses for for a Non-Banking Financial Company (NBFC) based on transaction and customer data using machine learning techniques. The goal is to build a model that accurately classifies whether a loan application will be approved or denied, based on historical transactional data

## Task Summary: 

The primary goal of NBFC is to:

   • Develop a classification model to predict loan repayment behavior.

   • Identify potential defaulters and non-defaulters.

   • Enhance risk assessment and improve the loan approval process.

## Repository Structure

```bash
DSW-Classification-Problem
├── Dataset
│   ├── test_data.xlsx
│   ├── train_data.xlsx
├── Problem Statement
│   ├── DSW_ML_Problem_Statement.pdf
├── Solution Notebooks
│   ├── eda.ipynb
│   ├── ModelTraining_Evaluation.ipynb
├── Rutuja Patil.zip
├── LICENSE
└── README.md
```

## Data Overview: 

• Historic data: Loan disbursement application and their default and non-default 
status for past 2 years+ has been kept in the file. 

File name: `train_data.xlsx `

• Validation data: Loan disbursement application and their default and non-default 
status for past 3 months has been kept in the file. 

File name: `test_data.xlsx` 

## Key Features:

`customer_id`: Represents the unique identifier for the customer.  
`transaction_date`: The date of the transaction.  
`sub_grade`: Sub-grade information.  
`term`: Loan term details.  

**Target variable:**  
`loan_status`: (`1` for default, `0` for non-default)

# Workflow

1. Exploratory Data Analysis (EDA):

      • Analyze the dataset to uncover patterns and relationships.
  
      • Visualize key features and explore correlations with loan repayment behavior.

2. Data Preprocessing:

      • Clean and preprocess the data, including handling missing values and outliers.

      • Parse datetime features (e.g., transaction date) and extract relevant information like year, month, day, hour, and minute.

3. Feature Engineering:

      • Encode categorical variables (e.g., loan status, customer demographics) into numerical formats.

      • Split the data into input features (X) and target variable (y), where the target is the loan repayment behavior (default or non-default).

4. Model Selection & Training:

      • Classification models USED: `Decision Tree`, `Logistic Regression`, `XGBoost`, `KNN` and `Naive Bayes`
 
      • Used an object-oriented, class-based approach with methods for data loading, preprocessing, training, testing, and prediction.
  
      • Tune hyperparameters using GridSearchCV for optimal model configuration.

5. Model Evaluation:

      • Evaluate model performance on the test set using metrics like accuracy, confusion matrix, precision, recall, and F1-score.

      • Assess the model's ability to classify defaulters and non-defaulters accurately.



# Installation and Usage
Ensure you have the following installed:

• Python 3.7+

• pip

# Setup
To clone this repository, run the following command in your terminal:

```bash
git clone https://github.com/Rutuja1193/DSW-Classification-Problem.git
```

Navigate to the project directory:
```bash
cd DSW-Classification-Problem
```
Run the notebooks:

• EDA: `Solution notebooks/eda.ipynb`

• Model Training & Evaluation: `Solution notebooks/ModelTraining_Evaluation.ipynb`
