# Classification problem for Loan Default Prediction
## Task Summary: 

The NBFC is developing a classification model to predict loan repayment behaviour, 
specifically identifying potential defaulters and non-defaulters. The primary goal is to 
enhance risk assessment and improve the loan approval process. 

## Data Overview: 

• Historic data: Loan disbursement application and their default and non-default 
status for past 2 years+ has been kept in the file. File name: train_data.xlsx 

• Validation data: Loan disbursement application and their default and non-default 
status for past 3 months has been kept in the file. File name: test_data.xlsx 

## Key Features:

<span style="background-color: yellow;">customer_id</span>: Represents the unique identifier for the customer.
<span style="background-color: yellow;">transaction_date</span>: The date of the transaction.
<span style="background-color: yellow;">sub_grade</span>: Sub-grade information.
<span style="background-color: yellow;">term</span>: Loan term details.

Target variable: <span style="background-color: yellow;">loan_status</span>: (1 for default, 0 for non-default)

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

EDA: Solution notebook/eda.ipynb

Model Training & Evaluation: Solution notebook/ModelTraining_Evaluation.ipynb
