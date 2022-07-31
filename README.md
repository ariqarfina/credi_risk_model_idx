# Modelling for Credit Risk Management (In collaboration with Rakamin Academy)

We are id/x partners consultants. We have a client, Credifo Bank, an Indonesian Fintech Startup that is developing a Credit Risk Management system. For Credifo Bank, we were tasked with developing a model that predicts good credit risk. We were given a dataset by Credifo Bank, namely Loan Dataset from 2007 - 2014

# What's the Problem?

![image](https://user-images.githubusercontent.com/101324931/182020045-739be3aa-5952-4047-ad58-68c6a0cd8318.png)

Customers who take loans at Credifo Bank are increasing every year. However, every year, customers who are detected by bad loans* are increasingly following as well. It can be seen in this dataset that 11.87% of Bad Loaners were detected.

# Goal & Objective

Goal:

- Reducing the risk of default, which can harm the Company

Objective: 

- Create a model that can classify credit risk management
- Making credit risk management

# Model & Evaluation

![tabelll](https://user-images.githubusercontent.com/101324931/182020137-f1fc00a4-6774-42e9-a044-8e45c50c2f24.jpg)

From the results of the comparison above, we determine that the Decision Tree and Logistic Regression are the models to be used, because the Precision value is quite high and best fit. We will look at the feature importance to make credit risk management. We use Precision as the evaluation.

# Credit Risk Management with Log Reg Model (Based on Feature Importance and EDA):

- The most important factor in determining whether a borrower is eligible for a Good Loan or a Bad Loan is their credit score. According to EDA results, Credit Score G is the lowest grade that is risky and may result in a default.
- Income is the second most important factor in determining whether a loan is good or bad. According to the EDA results, bad loaners are dominated by Low Income, but this needs to be reviewed further with several other features.
- Mortgage home owners are preferred borrowers. Borrowers with Mortgage home status, according to our analysis, are more accustomed to paying an installment.
- Credit card borrowers are prioritized over other types of borrowers. Credit card users are accustomed to making installment payments, and the risk of default may be reduced as a result.
- Borrowers with a 60-month repayment period are more likely to have their loans approved. The longer the loan period, the easier it is to pay the installments with low installments to make it easier for customers and reduce the risk of default. The interest rate rises as the payment period lengthens.
- Loan Amount is a relatively minor feature. The greater the loan amount requested by the customer, the greater the risk of default.
