# Credit Classifier
## Medium Post: https://medium.com/@luislopez_62329/enhancing-credit-risk-prediction-with-crsp-dm-89a789fca0d5

This project is a part of the AAI-501 course in the Applied Artificial Intelligence Program at the University of San Diego (USD). <br/>

-- Project Status: [Completed]

## Installation
1. Open a terminal/command prompt
2. macOS w/ homebrew
    open a terminal and enter:
    brew install python
3. Windows
    open a powershell window and enter: 
    winget install -e --id Python.Python.3
4. In the same CLI install the following packages
    pip install numpy
    pip install pandas
    pip install matplotlib
    pip install seaborn
    pip install plotly
    pip install scikit-learn
    pip install ucimlrepo
    pip install notebook
    pip install scikit-learn
    pip install imbalanced-learn

6. Download a copy of the Jupyter Notebook from the repo
7. In terminal/powershell enter:
    jupyter notebook
8. In the localhost window that is launched from the above command, navigate to downloaded notebook directory and open
  
## Project Intro/Objective
This project centers on classifying good vs bad credit risk

Dataset URL: https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data

## Partner(s)/Contributor(s)  
•	Andrew Roehr, Scott Hogan and Luis Lopez <br/>

## Methods Used
•	Machine Learning<br/>
•	Data Visualization<br/>
•	Data Manipulation<br/>

## Technologies
•	Python<br/>
•	Jupyter Notebook<br/>

## Project Description
Our project aims to test algorithms that classifies good vs bad credit risks based on financial information

### Dataset Description
Data Source: <br/>
 	•	The dataset was obtained from https://archive.ics.uci.edu/dataset/144/statlog+german+credit+data
### Data Dictionary
Attribute 1:  (qualitative)
	       Status of existing checking account
               A11 :      ... <    0 DM
	       A12 : 0 <= ... <  200 DM
	       A13 :      ... >= 200 DM /
		     salary assignments for at least 1 year
               A14 : no checking account

Attribute 2:  (numerical)
	      Duration in month

Attribute 3:  (qualitative)
	      Credit history
	      A30 : no credits taken/
		    all credits paid back duly
              A31 : all credits at this bank paid back duly
	      A32 : existing credits paid back duly till now
              A33 : delay in paying off in the past
	      A34 : critical account/
		    other credits existing (not at this bank)

Attribute 4:  (qualitative)
	      Purpose
	      A40 : car (new)
	      A41 : car (used)
	      A42 : furniture/equipment
	      A43 : radio/television
	      A44 : domestic appliances
	      A45 : repairs
	      A46 : education
	      A47 : (vacation - does not exist?)
	      A48 : retraining
	      A49 : business
	      A410 : others

Attribute 5:  (numerical)
	      Credit amount

Attibute 6:  (qualitative)
	      Savings account/bonds
	      A61 :          ... <  100 DM
	      A62 :   100 <= ... <  500 DM
	      A63 :   500 <= ... < 1000 DM
	      A64 :          .. >= 1000 DM
              A65 :   unknown/ no savings account

Attribute 7:  (qualitative)
	      Present employment since
	      A71 : unemployed
	      A72 :       ... < 1 year
	      A73 : 1  <= ... < 4 years  
	      A74 : 4  <= ... < 7 years
	      A75 :       .. >= 7 years

Attribute 8:  (numerical)
	      Installment rate in percentage of disposable income

Attribute 9:  (qualitative)
	      Personal status and sex
	      A91 : male   : divorced/separated
	      A92 : female : divorced/separated/married
              A93 : male   : single
	      A94 : male   : married/widowed
	      A95 : female : single

Attribute 10: (qualitative)
	      Other debtors / guarantors
	      A101 : none
	      A102 : co-applicant
	      A103 : guarantor

Attribute 11: (numerical)
	      Present residence since

Attribute 12: (qualitative)
	      Property
	      A121 : real estate
	      A122 : if not A121 : building society savings agreement/
				   life insurance
              A123 : if not A121/A122 : car or other, not in attribute 6
	      A124 : unknown / no property

Attribute 13: (numerical)
	      Age in years

Attribute 14: (qualitative)
	      Other installment plans 
	      A141 : bank
	      A142 : stores
	      A143 : none

Attribute 15: (qualitative)
	      Housing
	      A151 : rent
	      A152 : own
	      A153 : for free

Attribute 16: (numerical)
              Number of existing credits at this bank

Attribute 17: (qualitative)
	      Job
	      A171 : unemployed/ unskilled  - non-resident
	      A172 : unskilled - resident
	      A173 : skilled employee / official
	      A174 : management/ self-employed/
		     highly qualified employee/ officer

Attribute 18: (numerical)
	      Number of people being liable to provide maintenance for

Attribute 19: (qualitative)
	      Telephone
	      A191 : none
	      A192 : yes, registered under the customers name

Attribute 20: (qualitative)
	      foreign worker
	      A201 : yes
	      A202 : no

8.  Cost

(1 = Good,  2 = Bad)

the rows represent the actual classification and the columns
the predicted classification.

It is worse to class a customer as good when they are bad (5), 
than it is to class a customer as bad when they are good (1).

### Questions and Hypotheses
Project Focus:<br/>
	◦	What classifying algorithm will perform better at classifying good vs bad credit risk?<br/>

### Data Analysis, Visualization, and Modeling
Our approach involves:<br/>
	•	Data Cleaning and Preprocessing:<br/>
		◦	Handling missing values (if any).<br/>
		◦	Standardizing features.<br/>
	•	Exploratory Data Analysis (EDA):<br/>
		◦	Simulating performance scores.<br/>
		◦	Balancing dataset.<br/>
	•	Feature Engineering:<br/>
	◦	Classification: Naive-Bayes Classifier, XGBOOST, Random Forest.<br/>

### Roadblocks
Challenges:<br/>
	•	Data Quality: Ensuring data consistency, feature selection and accuracy.<br/>
	•	Model Selection: Choosing appropriate algorithms.<br/>
	•	Interpretability: Analyzing, reporting and evaluating algorithm performance.<br/>

## MIT License

## Acknowledgments
We would like to thank Professor Andre Van Benschoten, PhD, for his coursework and guidance. 
