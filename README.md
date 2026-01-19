# AIML_Assignment - Credit Risk Scoring

## Project Overview
This project focuses on credit risk scoring using historical loan data from LendingClub, a US-based peer-to-peer lending platform. The aim is to support loan approval decisions and reduce financial losses caused by borrower default by applying data analysis and machine learning techniques.

## Business Context
When a customer applies for a loan, the company must decide whether to approve or reject the application. This decision involves two key risks:
- Rejecting a good applicant leads to a loss of potential customers and missed profit.
- Approving a bad applicant increases the risk of default and financial loss.

## Loan Outcomes
After a loan is approved, it can result in one of the following outcomes:
- Fully Paid: the borrower repaid the loan completely.
- Current: the borrower is making payments on time.
- Charged-off: the borrower defaulted and stopped making payments.

These outcomes are used to define the target variable for credit risk prediction.

## Dataset
The project uses large CSV datasets for training and evaluation. Due to their size, datasets are managed using Git Large File Storage (Git LFS), while all other files are stored using standard Git.

## Project Structure
data/
- raw/ – original datasets  
- processed/ – cleaned and processed data  
- notebooks/ – exploratory data analysis and model development  
- src/ – preprocessing and modeling code  
- README.md  
- .gitattributes – Git LFS configuration  

## Setup
git lfs install  
git clone https://github.com/anvitho07/AIML_Assignment_Credit_Risk_Scoring.git  
cd AIML_Assignment_Credit_Risk_Scoring  

## Technologies Used
Python, Pandas, NumPy, Scikit-learn, Jupyter Notebook, Git, Git LFS

## Author
Anvith Amin
MSc Industrial Engineering & International Management  
Specialization: Data Science in Business
