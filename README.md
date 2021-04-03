Challenge of module 1

This code was written with the purpose of automatizing the task of loan analysis.

Part 1: Automate the Calculations:
I used loops and variables to automate the calculations for the loan portfolio summaries.

Part 2: Analyze Loan Data:
With the help of the function get() I extracted certain values from a dictionary and used them to calculate the present value.

Part 3: Perform Financial Calculations:
I created a financial function with the purpose of it having the ability to be reused with new data values.

Part 4: Conditionally Filter Lists of Loans
I looped through a series of loans for a company with the purpose of considering and filtering them to find the inexpensives ones


Part 5: Save the Results:
In this part of the task I created a CSV file with the purpose of showing the data as a spreasheet 

Part 6: Results:
$ python loan_analyzer.py
The total number of loans is: 5
The total loan amount is: 2750
The average loan amount is: 550.0
Future value of the loan is: 1000
Remaining months: 9
present value with 20% of discount rate is:  861.77
The loan is too expensive and not worth the price
The present value of the loan is:  820.08
 The list of inexpensive loans is:[{'loan_price': 500, 'remaining_months': 13, 'repayment_interval': 'bullet', 'future_value': 1000}, {'loan_price': 200, 'remaining_months': 16, 'repayment_interval': 'bullet', 'future_value': 1000}]
