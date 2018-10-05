# germancreditdata
The dataset german_credit.csv has been processed according to the below set of purpose codes: 

Purpose codes:
    0-car(new)
    1-car(old)
    2 : furniture/equipment 
    3 : radio/television 
    4 : domestic appliances 
    5 : repairs 
    6 : education 
    7 : (vacation - does not exist?) 
    8 : retraining 
    9 : business 
    10 : others
Payment status of previous credit:
    0 : no credits taken/ all credits paid back duly 
    1 : all credits at this bank paid back duly 
    2 : existing credits paid back duly till now 
    3 : delay in paying off in the past 
    4 : critical account/ other credits existing (not at this bank) 
Sex and marital status:
    1 : male : divorced/separated 
    2 : female : divorced/separated/married 
    3 : male : single 
    4 : male : married/widowed 
    5 : female : single 
Guarantors:
    1 : none 
    2 : co-applicant 
    3 : guarantor 
Type of Apartment:
    1: rent
    2: own
    3: for free
Occupation:
    1 : unemployed/ unskilled - non-resident 
    2 : unskilled - resident 
    3 : skilled employee / official 
    4 : management/ self-employed/highly qualified employee/ officer 
Most valuable available asset:
    1 : real estate 
    2 : if not A121 : building society savings agreement/ life insurance 
    3 : if not A121/A122 : car or other, not in attribute 6 
    4 : unknown / no property
    
    
    
When a bank receives a loan application, based on the applicant’s profile the bank has to make a decision regarding whether to go ahead with the loan approval or not. Two types of risks are associated with the bank’s decision:
If the applicant is a good credit risk, i.e. is likely to repay the loan.
If the applicant is a bad credit risk, i.e. is not likely to repay the loan, then approving the loan to the person results in a financial loss to the bank
It may be assumed that the second risk is a greater risk, as the bank had a higher chance of not being paid back the borrowed amount. So its on the part of the bank or other lending authority to evaluate the risks associated with lending money to a customer.
This project aims at building a data model based on the applicant’s demographic and socio-economic profiles to assess the risk of lending loan to the customer. The data model predicts if the applicant will repay the loan or not.


The data model used in this case is Logistic Regression. 
The author will add comments to the code and include other data models such as Random Forest, Decision Tree and run a comparison between these models soon.
Due credit is to be given to the author's classmate and friend Neha A for helping him throughout the course of the project and with the presenation as well.
