# Lending Club
> Leading Club Project Details......


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Project Background
This project involves risk analytics in the banking and financial services domain. Specifically, it focuses on a consumer finance company that specializes in lending various types of loans to urban customers. The company needs to make informed decisions regarding loan approvals based on applicants' profiles to minimize financial losses. The primary goal is to identify patterns that indicate whether an applicant is likely to default on a loan, enabling the company to make more informed lending decisions.

- Business Problem
The key business problem addressed by this project is to minimize the risk of credit loss due to loan defaults. There are two types of risks associated with loan approval decisions:

Loss of business: If an applicant who is likely to repay the loan is not approved, the company loses potential business.
Financial loss: If an applicant who is likely to default on the loan is approved, the company incurs a financial loss.
By identifying risky applicants who are likely to default, the company can reduce the amount of credit loss. This involves understanding the driving factors behind loan defaults using Exploratory Data Analysis (EDA).

-Dataset
The dataset used in this project contains information about past loan applicants and their repayment behavior, including whether they defaulted on their loans. This data spans loans issued from 2007 to 2011 and includes various consumer attributes (such as demographics and credit history) and loan attributes (such as loan amount and interest rate).

-Key Scenarios in the Dataset:
-Loan Accepted:

Fully Paid: The applicant has fully repaid the loan.
Current: The applicant is currently repaying the loan.
Charged-off: The applicant has defaulted on the loan.
Loan Rejected:

The applicant did not meet the company's requirements, so no transactional history is available for these applicants in the dataset.
The aim is to use this dataset to identify the factors that strongly indicate a likelihood of default, thereby helping the company in its portfolio and risk assessment.

- Data Sources
Loan Dataset: Download Link
Data Dictionary: Download Link
This project will employ EDA techniques to analyze the dataset, uncover patterns, and derive insights that will assist in reducing credit losses due to loan defaults.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The analysis revealed significant insights into the distribution and relationship of various 
  features with loan status. The logistic regression model performed well in predicting loan 
  status, with a reasonable accuracy
- Accuracy: 85.78%
  High accuracy but poor sensitivity to defaults suggests model imbalance.
  Recommendations for improving model sensitivity and reducing false negatives
- The confusion matrix provides a detailed breakdown of true positives, true negatives, false 
  positives, and false negatives.
  Precision (0): 86% - Predicted non-default correctly.
  Precision (1): 0% - Failed to predict any defaults correctly.
  Recall (0): 100% - Identified all non-default correctly.
  Recall (1): 0% - Missed all defaults.
- The classification report includes precision, recall, and F1-score for each class.
   precision recall f1-score support
   0 0.86 1.00 0.92 4187
   1 0.00 0.00 0.00 694
  accuracy 0.86 4881
  macro avg 0.43 0.50 0.46 4881
  weighted avg 0.74 0.86 0.79 4881


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas
- matplotlib
- seaborn
- scikit-learn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- Dataset: [Link to the source of the dataset]
- Scikit-learn Documentation: https://scikit-learn.org/
- Seaborn Documentation: https://seaborn.pydata.org/
- Pandas Documentation: https://pandas.pydata.or


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
