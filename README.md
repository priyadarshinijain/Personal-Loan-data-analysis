# Personal-Loan-data-analysis

Project Overview
This project focuses on analyzing a dataset related to personal loans offered by a bank. The goal is to uncover patterns in customer behavior and loan acquisition trends using various data analysis and visualization techniques.

## Dataset
The dataset used in this analysis is named Bank_Personal_Loan_Modelling.xlsx and contains the following columns:
- *ID*: Customer ID
- *Age*: Customer's age
- *Experience*: Years of professional experience
- *Income*: Annual income of the customer (in thousands)
- *ZIP Code*: Customer's residential ZIP code
- *Family*: Number of family members
- *CCAvg*: Average monthly spending on credit cards
- *Education*: Level of education (1 = undergraduate, 2 = graduate, 3 = advanced/doctoral)
- *Mortgage*: Value of the customer's mortgage
- *Personal Loan*: Whether the customer has accepted a personal loan from the bank
- *Securities Account*: Whether the customer holds a securities account
- *CD Account*: Whether the customer holds a certificate of deposit (CD) account
- *Online*: Whether the customer uses online banking
- *CreditCard*: Whether the customer has a credit card issued by the bank

## Libraries Used
The following Python libraries are used in the analysis:
- pandas for data manipulation
- numpy for numerical computations
- seaborn for data visualization
- matplotlib for plotting static charts
- plotly.express for interactive plots
- warnings to suppress unnecessary warnings

## Key Steps
1. *Data Loading*: Loaded the data from the Excel file and inspect the first few rows using .head() function.
2. *Data Cleaning*: Handled missing values, removed duplicates, and performed other necessary data preprocessing.
3. *Exploratory Data Analysis (EDA)*: Analyze various features such as income distribution, loan acceptance rates, type of customers and correlations between features.
4. *Data Visualization*: Used seaborn, matplotlib, and plotly to visualize trends and extracting insights from the data.
