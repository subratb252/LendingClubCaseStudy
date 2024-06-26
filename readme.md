\*\*\*Files loan.csv: The dataset used for the analysis.
loan_data_analysis.py: Python script containing the data preprocessing,
analysis, and model development code.
Loan_Data_Analysis_and_Prediction_Report.pdf: Detailed project report
with analysis, visualizations, and model evaluation.

README.txt: Description of the project and instructions for running the
code.

\*\*\*Requirements The project requires the following Python libraries:

pandas matplotlib seaborn scikit-learn

\*\*\*Install the required libraries using pip:

pip install pandas matplotlib seaborn scikit-learn

\*\*\*\*Running the Code 1. Ensure that loan.csv is in the same
directory as the Lending Club Case Study_SubratBiswal.py script. 2. Open
a terminal or command prompt. 3. Navigate to the directory containing
the files. 4. Run the Python script python Lending Club Case
Study_SubratBiswal.py

\*\*\*Steps in the Script 1. Load the Dataset: Reads the dataset from
loan.csv. 2. Data Cleaning: Drops columns with more than 50% missing
values. Drops rows with any missing values. 3. Removes percentage signs
from the int_rate column and converts it to float. 4. Exploratory Data
Analysis: Univariate analysis for categorical and numerical variables.
Bivariate analysis between loan status and other variables. 5. Data
Preparation: Encodes categorical variables using label encoding. Selects
features for the model. 6. Model Development: Splits the data into
training and testing sets. Trains a logistic regression model. 7. Model
Evaluation: Makes predictions on the test set. 8. Evaluates the model
using accuracy, confusion matrix, and classification report. 9.Results
The script outputs visualizations for data analysis. The model\'s
accuracy, confusion matrix, and classification report are printed.
10.Conclusion The project provides insights into the factors affecting
loan status and demonstrates the use of logistic regression for
predicting loan defaults.
