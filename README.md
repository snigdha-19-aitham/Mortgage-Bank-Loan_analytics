Mortgage Bank Loan Analytics
Project Overview
Banks can utilize this project to analyze mortgage loans and market trends using Data Science techniques. The system provides detailed insights into mortgage loans, helping mortgage brokers identify trading opportunities and enabling CFOs to perform "what-if" scenarios for balance sheet management.

Loan File Template Fields
The following attributes are included in the loan file template:

Loan ID: Unique identifier for each loan.
Loan Type: Fixed rate, balloon loan, ARM, or AMP (alternative mortgage product).
Balance: Outstanding loan balance.
Loan Program Type: Conforming loan, FHA/VA loan, jumbo loan, or sub-prime loan.
Current Coupon Rate: Applicable interest rate.
Amortization Type: Original amortization term.
Maturity: Remaining term of the loan.
FICO Score: Updated borrower credit score.
LTV: Current loan-to-value ratio.
Loan Size: Total loan amount.
Loan Origination Location: City and zip code where the loan originated.
Unit Types: Property types (e.g., single-family, multi-family).
Machine Learning Models Evaluated
Random Forest (Best Performer): Lowest error and highest accuracy.
Decision Tree: Second-best performer.
Support Vector Machine (SVM): Moderate performance.
Support Vector Regression (SVR): Lowest performance.
Linear Regression: Used for baseline comparisons.
Logistic Regression: Classification-based analysis.
k-Nearest Neighbors (k-NN): Additional model for performance evaluation.
The Random Forest model consistently provided the most accurate predictions of daily mortgage applications, with the lowest percent error.

Technologies Used
Languages: Python
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib
Tools: Jupyter Notebook
Key Features
Detailed Loan Profiling: Provides granular information on loan attributes.
Predictive Analytics: Forecasts mortgage applications per day.
Scenario Modeling: Enables financial "what-if" scenarios for balance sheets.
Business Impact
Increased loan approval efficiency through predictive analytics.
Empowered data-driven decision-making for financial planning.
