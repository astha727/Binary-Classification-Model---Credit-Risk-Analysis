# Binary-Classification-Model---Credit-Risk-Analysis
CAPSTONE PROJECT - Binary Classification Model for Credit Defaulters  A binary classification system involves a system that generates ratings for each occurrence, which, by ordering them, are turned into rankings, which are then compared to a threshold. Occurrences with rankings above the threshold are declared positive, and occurrences below the threshold are declared negative.   To develop two different predictive models to determine which applicants for credit cards should be accepted and which rejected. The first model will focus on minimizing default risk, and  second on maximizing bank profits.   The data has 400 applicants, first 200 applicants were kept for Training the model and remaining 200 were kept to test the sensitivity of the model  

Model A  

Default Risk Model  Since, we had to design a binary classification model for credit card risk, it seemed obvious that Credit card debt, automobile debt and income were the direct linked metric. So, I decided to first find out debt to income ratio, which was calculated :-  Debt to Income Ratio = (CC debt + Automobile debt) / Income (I could have included years at employment and age but it would have complicated my model and i wouldn't have gotten correct results)

MODEL B						
						
						
Profitability Model		

The bank decided to use Third party data (Eggertopia Scores) which gave much better AUC. The bank wants to know if thety apply these scores to the model How much profit they can earn						
						
For second model I first calculated Z scores using the linest function with Y = profits/loss and X = all 6 metrics in training set. The beta values are generated as 						
x_6 Coeff	x_5 Coeff	x_4 Coeff	x_3 Coeff	x_2 Coeff	x_1 Coeff	Constant
x_6 Std Err	x_5 Std Err	x_4 Std Err	x_3 Std Err	x_2 Std Err	x_1 Std Err	Constant Std Err
