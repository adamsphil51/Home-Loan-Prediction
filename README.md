# Home-Loan-Prediction

1.1 Introduction

    Dream Housing Finance company deals in all home loans.
    They have presence across all urban, semi urban and rural areas.
    Customer first apply for home loan after that company validates the customer eligibility for loan.
    Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form.
    These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others.
    To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers.

1.2 Problem Statement

    This is a standard supervised classification task.
    A classification problem where we have to predict whether a loan would be approved or not.
    In a classification problem, we have to predict discrete values based on a given set of independent variable(s).Classification can be of following types:
    Supervised: The labels are included in the training data and the goal is to train a model to learn to predict the labels from the features.
    
    Binary Classification : In this classification we have to predict either of the two given classes. For example: classifying the gender as male or female, predicting the result as win or loss, etc.
    
    Multiclass Classification : Here we have to classify the data into three or more classes. For example: classifying a movie's genre as comedy, action or romantic, classify fruits as oranges, apples, or pears, etc.

1.3 About the dataset

Below are some of the factors which I think can affect the Loan Approval (dependent variable for this loan prediction problem):

    Salary: Applicants with high income should have more chances of loan approval.
    
    Previous history: Applicants who have repayed their previous debts should have higher chances of loan approval.
    
    Loan amount: Loan approval should also depend on the loan amount. If the loan amount is less, chances of loan approval should be high.
    
    Loan term: Loan for less time period and less amount should have higher chances of approval.
    
    EMI: Lesser the amount to be paid monthly to repay the loan, higher the chances of loan approval.
    
    These are some of the factors which i think can affect the target variable, you can come up with many more factors
